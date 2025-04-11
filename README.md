# Dự án website thương mại điện tử bán hàng thời trang 🚀

> Hệ thống thương mại điện tử bán hàng thời trang

## ✨ Tính năng

- ✅ Quản lý danh mục, sản phẩm, khách hàng, đơn hàng
- ✅ Đăng ký, đăng nhập, xác thực với JWT
- ✅ Giao diện sáng tối, ngôn ngữ tiếng anh - tiếng việt
- ✅ Tìm kiếm, lọc và sắp xếp
- ✅ Phân quyền người dùng
- ✅ Nhắn tin thời gian thực với socket
- ✅ Thanh toán online với zalopay
- ✅ Giao diện trực quan dễ sử dụng

## 🔧 Công nghệ sử dụng

- 🔥 **Frontend**: ReactJS, Vite, Tailwind, Redux Toolkit, Formik, Yup, Ant Design
- ⚡ **Backend**: Node.js, Express, Socket, Mysql, Redis, nodemailer
- 🔗 **Authentication**: JWT
- 🛢 **Hosting**: Vercel (Frontend), Render (Backend)

## 📎 Link github

```sh
https://github.com/phucngdev/TM-FE.git
```

### 1️⃣ **Yêu cầu**

- Node.js >= 16
- Database

### 2️⃣ **Clone the repository**

```sh
git clone https://github.com/phucngdev/TM-FE.git
cd client
```

```sh
git clone https://github.com/phucngdev/TM-FE.git
cd server
```

### 3️⃣ **Install dependencies**

```sh
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

### 5️⃣ **Chạy dự án**

#### 🌐 **Frontend**

```sh
npm run dev
```

#### 💻 **Backend**

```sh
npm start
```

## 📌 Danh sách API Endpoints (sẽ bổ sung sau)

| Method | Endpoint            | Mô tả                                    | Request Body (JSON) | Token  |
| ------ | ------------------- | ---------------------------------------- | ------------------- | ------ |
| `GET`  | `/api/v1/tasks`     | Lấy danh sách tất cả công việc           | ❌ Không cần        | ✅ Cần |
| `GET`  | `/api/v1/tasks/:id` | Lấy thông tin chi tiết của một công việc | ❌ Không cần        | ✅ Cần |

---

## 📩 Contact

- 📌 Nhóm 5 - Hệ thống thương mại điện tử thời trang
