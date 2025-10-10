OJECT-PHASE-1

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
![Docker Architecture](public/results/docker.png)
### 🔑 Đăng ký người dùng
![Register](public/results/register.png)

### 🔐 Đăng nhập người dùng
![Login](public/results/login.png)

---

## 🛍️ Product Service

### ➕ Thêm sản phẩm
![Product](public/results/product.png)

### 🔎 Lấy danh sách sản phẩm
![Get Product](public/results/getProduct.png)

---

## 📦 Order Service

### 🧾 Đặt hàng sản phẩm
![Order Product](public/results/orderProduct.png)

---

## 🐇 RabbitMQ Service

Hệ thống sử dụng **RabbitMQ** để giao tiếp giữa các service (Pub/Sub model):

![RabbitMQ](public/results/rabbit.png)

---

## ⚙️ Công nghệ sử dụng

- **Node.js / Express.js**
- **MongoDB**
- **RabbitMQ**
- **Docker**
- **JWT Authentication**
- **RESTful API**
