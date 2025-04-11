```markdown
## Understanding the `useEffect` Hook in React

The `useEffect` hook in React is a powerful tool for managing side effects in functional components. Side effects are actions that interact with the outside world, such as:

*   Fetching data from an API
*   Updating the DOM directly
*   Setting up subscriptions
*   Using timers

`useEffect` allows you to perform these side effects after React has rendered the component.  It's essentially a combination of `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` in class components.

### Basic Usage

The basic syntax for `useEffect` is:

```javascript
import React, { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    // This code will run after the component renders
    console.log('Component rendered!');

    // Optional cleanup function (runs when the component unmounts or re-renders)
    return () => {
      console.log('Component unmounted or re-rendered!');
    };
  }, []); // Empty dependency array means this effect runs only once, on mount

  return (
    <div>
      Hello, world!
    </div>
  );
}
```

**Explanation:**

*   The first argument to `useEffect` is a function that contains the side effect you want to perform.
*   The second argument is an optional array of dependencies. This array tells React when to re-run the effect.

### Dependency Array

The dependency array is crucial for controlling when the effect runs. Here's how it works:

*   **Empty Array (`[]`):** The effect runs only once, after the initial render (similar to `componentDidMount`).  This is useful for things like fetching data once when the component loads.
*   **Array with Variables (`[count, data]`):** The effect runs whenever any of the variables in the array change. This is useful for updating the DOM based on state changes.
*   **No Array (omitted):** The effect runs after *every* render. This can lead to performance issues if not used carefully.

### Cleanup Function

The function returned from the `useEffect` callback is called the "cleanup function."  It allows you to undo the side effect when the component unmounts or re-renders.  This is important for preventing memory leaks and ensuring that your component behaves correctly.

**Example: Cleaning up a subscription:**

```javascript
import React, { useState, useEffect } from 'react';

function MySubscriptionComponent() {
  const [data, setData] = useState(null);

  useEffect(() => {
    const subscription = someExternalLibrary.subscribe(newData => {
      setData(newData);
    });

    return () => {
      // Unsubscribe when the component unmounts or re-renders
      subscription.unsubscribe();
    };
  }, []);

  return (
    <div>
      Data: {data}
    </div>
  );
}
```

### Key Takeaways

*   `useEffect` is the primary way to manage side effects in functional React components.
*   The dependency array controls when the effect runs.
*   The cleanup function prevents memory leaks and ensures proper behavior.
*   Use `useEffect` responsibly to avoid performance issues.
```

```markdown
## Tìm hiểu Hook `useEffect` trong React

Hook `useEffect` trong React là một công cụ mạnh mẽ để quản lý side effect trong các functional component. Side effect là những hành động tương tác với thế giới bên ngoài, ví dụ như:

*   Lấy dữ liệu từ một API
*   Cập nhật DOM trực tiếp
*   Thiết lập subscriptions
*   Sử dụng timers

`useEffect` cho phép bạn thực hiện những side effect này sau khi React đã render component. Nó về cơ bản là sự kết hợp của `componentDidMount`, `componentDidUpdate` và `componentWillUnmount` trong các class component.

### Sử dụng cơ bản

Cú pháp cơ bản cho `useEffect` là:

```javascript
import React, { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    // Đoạn code này sẽ chạy sau khi component render
    console.log('Component rendered!');

    // Optional cleanup function (chạy khi component unmount hoặc re-renders)
    return () => {
      console.log('Component unmounted or re-rendered!');
    };
  }, []); // Empty dependency array có nghĩa là effect này chỉ chạy một lần, khi mount

  return (
    <div>
      Hello, world!
    </div>
  );
}
```

**Giải thích:**

*   Tham số đầu tiên cho `useEffect` là một function chứa side effect mà bạn muốn thực hiện.
*   Tham số thứ hai là một array các dependency tùy chọn. Array này cho React biết khi nào cần chạy lại effect.

### Dependency Array

Dependency array là rất quan trọng để kiểm soát khi nào effect chạy. Đây là cách nó hoạt động:

*   **Empty Array (`[]`):** Effect chỉ chạy một lần, sau lần render đầu tiên (tương tự như `componentDidMount`). Điều này hữu ích cho những việc như lấy dữ liệu một lần khi component tải.
*   **Array với Variables (`[count, data]`):** Effect chạy bất cứ khi nào bất kỳ biến nào trong array thay đổi. Điều này hữu ích cho việc cập nhật DOM dựa trên những thay đổi state.
*   **Không có Array (bỏ qua):** Effect chạy sau *mỗi* lần render. Điều này có thể dẫn đến các vấn đề về hiệu suất nếu không được sử dụng cẩn thận.

### Cleanup Function

Function được trả về từ callback của `useEffect` được gọi là "cleanup function". Nó cho phép bạn hoàn tác side effect khi component unmount hoặc re-renders. Điều này quan trọng để ngăn chặn memory leaks và đảm bảo component của bạn hoạt động chính xác.

**Ví dụ: Dọn dẹp một subscription:**

```javascript
import React, { useState, useEffect } from 'react';

function MySubscriptionComponent() {
  const [data, setData] = useState(null);

  useEffect(() => {
    const subscription = someExternalLibrary.subscribe(newData => {
      setData(newData);
    });

    return () => {
      // Unsubscribe khi component unmount hoặc re-renders
      subscription.unsubscribe();
    };
  }, []);

  return (
    <div>
      Data: {data}
    </div>
  );
}
```

### Những điểm chính

*   `useEffect` là cách chính để quản lý side effect trong các functional React components.
*   Dependency array kiểm soát khi nào effect chạy.
*   Cleanup function ngăn chặn memory leaks và đảm bảo hành vi thích hợp.
*   Sử dụng `useEffect` một cách có trách nhiệm để tránh các vấn đề về hiệu suất.
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._