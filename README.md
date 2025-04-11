# Nhóm 5 - Dự án website thương mại điện tử bán hàng thời trang 🚀

> Hệ thống thương mại điện tử bán hàng thời trang

## ✨ Tính năng

- ✅ Quản lý danh mục, sản phẩm, khách hàng, đơn hàng
- ✅ Đăng ký, đăng nhập, xác thực với JWT
- ✅ Quản lý giỏ hàng
- ✅ Lịch sử đơn hàng, kiểm tra đơn hàng
- ✅ Giao diện sáng tối, ngôn ngữ anh - việt
- ✅ Tìm kiếm, lọc và sắp xếp
- ✅ Phân quyền người dùng
- ✅ Nhắn tin thời gian thực với socket
- ✅ Thanh toán online với zalopay
- ✅ Gửi mail thông báo
- ✅ Giao diện trực quan dễ sử dụng

## 🔧 Công nghệ sử dụng

- 🔥 **Frontend**: ReactJS, Vite, Tailwind, Redux Toolkit, Formik, Yup, Ant Design
- ⚡ **Backend**: NodeJS, Express, Socket, Mysql, Redis, Nodemailer, Firebase
- 🔗 **Authentication**: JWT
- 🛢 **Hosting**: Vercel (Frontend), Render (Backend)

### 1️⃣ **Yêu cầu**

- Node.js >= 16
- Mysql
- NPM

### 2️⃣ **Clone the repository**

```sh
git clone https://github.com/phucngdev/do-an-cnpm.git
```

### 3️⃣ **Install dependencies**

#### 🌐 **Frontend**

```sh
cd client
npm install
```

#### 💻 **Backend**

```sh
cd server
npm install
```

### 4️⃣ **Setup environment variables**

Tạo file `.env` và config: (Đã có sẵn không cần thực hiện bước này)

#### 🌐 **Frontend**

```
VITE_APP_ID=yourappid (zegocloud)
VITE_SECRET=yourkey
VITE_API_URL=yourlinkapi
VITE_SECRET_KEY=yourkey
```

#### 💻 **Backend**

```
MONGODB_URL=yoururldatabase
JWT_ACC_SECRET=yourkey
JWT_REF_SECRET=yourkey
VITE_SECRET_KEY=yourkey
```

Tạo database: cấu trúc database trong file `server/src/sql` (Chú ý thứ tự tạo các bảng)

### 5️⃣ **Chạy dự án**

#### 🌐 **Frontend**

```sh
cd client
npm run dev
```

#### 💻 **Backend**

```sh
cd server
npm start
```

## 📌 Danh sách API Endpoints (sẽ bổ sung sau)

| Method | Endpoint               | Mô tả                                    | Request Body (JSON) | Token        |
| ------ | ---------------------- | ---------------------------------------- | ------------------- | ------------ |
| `GET`  | `/api/v1/products`     | Lấy danh sách tất cả công việc           | ❌ Không cần        | ❌ Không cần |
| `GET`  | `/api/v1/products/:id` | Lấy thông tin chi tiết của một công việc | ❌ Không cần        | ❌ Không cần |

---

## 📩 Contact

- 📌 Nhóm 5 - Hệ thống thương mại điện tử bán hàng thời trang
