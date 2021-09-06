# chongdacap

Tiện ích trình duyệt giúp định danh đa cấp!

![showcase](https://github.com/phamleduy04/chongdacap/blob/main/github/showcase.jpg?raw=true)
![showcase2](https://github.com/phamleduy04/chongdacap/blob/main/github/showcase2.png?raw=true)

# Cách cài đặt
Tải qua link ở [đây](https://chrome.google.com/webstore/detail/chongdacap/joiiiinfpglkgklohagocnhfphajbamm)

# API
Các bạn có thể truy cập vào API của extension một cách dễ dàng:
- BaseURL: https://chongdacap.xyz/

-   **URL**
    
	   `/api/blacklist`
    
-   **Method:**
    
    `GET` 
    
-   **URL Params**
    
    **Optional:**
    
    `type=[array|json]` (default: json)
        
-   **Success Response:**
    
    -   **Code:**  200  
        **Content:**  `{"success":true,"response":[...],"length": x}` hoặc `["100009298983786","100036435135387", ...]`
