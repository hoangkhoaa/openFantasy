```markdown
# Understanding the API

This document outlines the basics of interacting with our API.

## Authentication

All requests to the API require authentication via an API key. You can obtain an API key from the [developer portal](https://example.com/developer).

Include your API key in the `X-API-Key` header:

```
X-API-Key: YOUR_API_KEY
```

## Endpoints

Here are some common endpoints:

*   `/users` - Manage user accounts.
    *   `GET` - Retrieve a list of users.
    *   `POST` - Create a new user.
*   `/products` - Manage product inventory.
    *   `GET` - Retrieve a list of products.
    *   `PUT` - Update an existing product.

## Data Formats

The API uses JSON for both requests and responses.  Here's an example of a request body for creating a new user:

```json
{
  "username": "newuser",
  "email": "newuser@example.com"
}
```

## Error Handling

The API returns standard HTTP status codes to indicate the success or failure of a request.  For example:

*   `200 OK` - Request successful.
*   `400 Bad Request` - Invalid request.
*   `401 Unauthorized` - Authentication failed.
*   `500 Internal Server Error` - Server error.

For more detailed error information, check the response body.
```
```

```vi
# Tìm hiểu về API

Tài liệu này trình bày những điều cơ bản về tương tác với API của chúng tôi.

## Xác thực

Tất cả các yêu cầu đến API đều yêu cầu xác thực thông qua một API key. Bạn có thể lấy API key từ [developer portal](https://example.com/developer).

Bao gồm API key của bạn trong header `X-API-Key`:

```
X-API-Key: YOUR_API_KEY
```

## Các Endpoint

Dưới đây là một số endpoint phổ biến:

*   `/users` - Quản lý tài khoản người dùng.
    *   `GET` - Lấy danh sách người dùng.
    *   `POST` - Tạo người dùng mới.
*   `/products` - Quản lý kho sản phẩm.
    *   `GET` - Lấy danh sách sản phẩm.
    *   `PUT` - Cập nhật một sản phẩm hiện có.

## Định dạng Dữ liệu

API sử dụng JSON cho cả yêu cầu và phản hồi. Dưới đây là một ví dụ về phần thân yêu cầu để tạo một người dùng mới:

```json
{
  "username": "newuser",
  "email": "newuser@example.com"
}
```

## Xử lý lỗi

API trả về các mã trạng thái HTTP tiêu chuẩn để cho biết sự thành công hay thất bại của một yêu cầu. Ví dụ:

*   `200 OK` - Yêu cầu thành công.
*   `400 Bad Request` - Yêu cầu không hợp lệ.
*   `401 Unauthorized` - Xác thực không thành công.
*   `500 Internal Server Error` - Lỗi máy chủ.

Để biết thông tin lỗi chi tiết hơn, hãy kiểm tra phần thân phản hồi.
```


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._