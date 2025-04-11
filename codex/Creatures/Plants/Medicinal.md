```markdown
# Setting up Your Development Environment

This guide outlines the steps to set up your development environment for working on the project.

## Prerequisites

Before you begin, ensure you have the following installed:

*   **Git:** Used for version control. Download from [https://git-scm.com/](https://git-scm.com/).
*   **Python 3.8+:**  The primary programming language. Download from [https://www.python.org/downloads/](https://www.python.org/downloads/).
*   **pip:** Python's package installer.  Usually comes with Python installations.  You can verify by running `python -m pip --version` in your terminal.
*   **Virtualenv:** For creating isolated Python environments. Install using `pip install virtualenv`.

## Setting Up a Virtual Environment

1.  Navigate to your project directory in the terminal:

    ```bash
    cd /path/to/your/project
    ```

2.  Create a virtual environment:

    ```bash
    virtualenv venv
    ```

3.  Activate the virtual environment:

    *   **On macOS/Linux:**

        ```bash
        source venv/bin/activate
        ```

    *   **On Windows:**

        ```bash
        venv\Scripts\activate
        ```

## Installing Dependencies

1.  Ensure your virtual environment is activated.
2.  Install the required packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

Once the dependencies are installed, you can run the application using:

```bash
python main.py
```

## Troubleshooting

*   If you encounter issues with package installations, try upgrading `pip`:

    ```bash
    pip install --upgrade pip
    ```

*   Ensure you're working within the activated virtual environment.

Good luck!
```
```markdown
# Thiết lập Môi trường Phát triển của Bạn

Hướng dẫn này phác thảo các bước để thiết lập môi trường phát triển của bạn để làm việc trên dự án.

## Điều kiện tiên quyết

Trước khi bắt đầu, hãy đảm bảo bạn đã cài đặt những thứ sau:

*   **Git:** Được sử dụng để kiểm soát phiên bản. Tải xuống từ [https://git-scm.com/](https://git-scm.com/).
*   **Python 3.8+:** Ngôn ngữ lập trình chính. Tải xuống từ [https://www.python.org/downloads/](https://www.python.org/downloads/).
*   **pip:** Trình cài đặt gói của Python. Thường đi kèm với các cài đặt Python. Bạn có thể xác minh bằng cách chạy `python -m pip --version` trong terminal của bạn.
*   **Virtualenv:** Để tạo các môi trường Python cô lập. Cài đặt bằng cách sử dụng `pip install virtualenv`.

## Thiết lập Môi trường Ảo

1.  Điều hướng đến thư mục dự án của bạn trong terminal:

    ```bash
    cd /path/to/your/project
    ```

2.  Tạo một môi trường ảo:

    ```bash
    virtualenv venv
    ```

3.  Kích hoạt môi trường ảo:

    *   **Trên macOS/Linux:**

        ```bash
        source venv/bin/activate
        ```

    *   **Trên Windows:**

        ```bash
        venv\Scripts\activate
        ```

## Cài đặt Các Phụ thuộc

1.  Đảm bảo môi trường ảo của bạn đã được kích hoạt.
2.  Cài đặt các gói cần thiết bằng cách sử dụng `pip`:

    ```bash
    pip install -r requirements.txt
    ```

## Chạy Ứng dụng

Sau khi các phụ thuộc được cài đặt, bạn có thể chạy ứng dụng bằng cách sử dụng:

```bash
python main.py
```

## Khắc phục sự cố

*   Nếu bạn gặp sự cố với việc cài đặt gói, hãy thử nâng cấp `pip`:

    ```bash
    pip install --upgrade pip
    ```

*   Đảm bảo bạn đang làm việc trong môi trường ảo đã kích hoạt.

Chúc may mắn!
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._