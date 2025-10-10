# EPROJECT-PHASE-1

## Example `.env` file:

### .env auth
- MONGODB_AUTH_URI= mongodb://host:port/database
- JWT_SECRET= your_jwt_sercet

### .env order
- MONGODB_AUTH_URI= mongodb://host:port/database
- JWT_SECRET= your_jwt_secret
- MONGODB_PRODUCT_URI=mongodb://host:port/database
- MONGODB_ORDER_URI=mongodb://host:port/database

### .env product
- MONGODB_AUTH_URI=mongodb://host:port/database
- JWT_SECRET=your_jwt_sercet
- MONGODB_PRODUCT_URI=mongodb://host:port/database

## Test all business logic with POSTMAN
### Kết quả chạy docker
![Docker Architecture](public/result/docker.png)
### 🔑 Đăng ký người dùng
![Register](public/result/register.png)

### 🔐 Đăng nhập người dùng
![Login](public/result/login.png)

---

## 🛍️ Product Service

### ➕ Thêm sản phẩm
![Product](public/result/product.png)

### 🔎 Lấy danh sách sản phẩm
![Get Product](public/result/getProduct.png)

---

## 📦 Order Service

### 🧾 Đặt hàng sản phẩm
![Order Product](public/result/orderProduct.png)

---

## 🐇 RabbitMQ Service

Hệ thống sử dụng **RabbitMQ** để giao tiếp giữa các service (Pub/Sub model):

![RabbitMQ](public/result/rabbit.png)

---

## ⚙️ Công nghệ sử dụng

- **Node.js / Express.js**
- **MongoDB**
- **RabbitMQ**
- **Docker**
- **JWT Authentication**
- **RESTful API**
