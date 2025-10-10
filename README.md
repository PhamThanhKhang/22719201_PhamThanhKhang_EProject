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
![results](public/results/docker.png)
---------------
### Kết quả test postman với register
![results](public/results/register.png)
---------------
### Kết quả test postman với login
![results](public/results/login.png)
---------------
### Kết quả test postman với tạo product
![results](public/results/product.png)
---------------
### Kết quả test postman với order product
![results](public/results/order.png)
---------------
### Kết quả test postman với xem product
![results](public/results/getProduct.png)
---------------
### Kết quả test postman với rabbit
![results](public/results/rabbit.png)
