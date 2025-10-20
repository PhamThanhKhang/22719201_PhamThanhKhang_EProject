Hệ thống bao gồm nhiều dịch vụ nhỏ (services) hoạt động độc lập, giao tiếp với nhau thông qua **API Gateway** và **message broker (RabbitMQ)**.  
Các dịch vụ chính:

- **Auth Service** – xử lý đăng ký, đăng nhập, xác thực người dùng.
- **Product Service** – quản lý danh mục, thêm/sửa/xóa sản phẩm.
- **Order Service** – xử lý đặt hàng, lưu trữ đơn hàng của người dùng.
- **API Gateway** – định tuyến request đến đúng service.
- **RabbitMQ** – dùng để truyền thông tin bất đồng bộ giữa các service.
  
## Test all business logic with POSTMAN
###  Đăng ký người dùng
![Register](public/results/register.png)

###  Đăng nhập người dùng
![Login](public/results/login.png)

---

## Product Service

### Thêm sản phẩm
![Product](public/results/product.png)

###  Lấy danh sách sản phẩm
![Get Product](public/results/getProduct.png)

---

##  Order Service

###  Đặt hàng sản phẩm
![Order Product](public/results/orderProduct.png)

---

##  RabbitMQ Service

Hệ thống sử dụng **RabbitMQ** để giao tiếp giữa các service (Pub/Sub model):

![RabbitMQ](public/results/rabbit.png)

---

##  Công nghệ sử dụng

- **Node.js / Express.js**
- **MongoDB**
- **RabbitMQ**
- **Docker**
- **JWT Authentication**
- **RESTful API**
