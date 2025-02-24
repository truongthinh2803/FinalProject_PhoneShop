# OnlineMobileSales

## Mô tả dự án
**OnlineMobileSales** là ứng dụng di động hỗ trợ mua bán điện thoại trực tuyến, với giao diện thân thiện, hiện đại và tích hợp nhiều chức năng quan trọng. Dự án sử dụng React Native, Tailwind CSS, và Firebase để xây dựng hệ thống quản lý sản phẩm, người dùng, giỏ hàng, và đơn hàng, cùng với chức năng phân quyền giữa Admin và User.

---

## Tính năng chính
### 1. **Dành cho người dùng (User)**  
- **Đăng ký/Đăng nhập**  
  - Đăng nhập/Đăng ký tài khoản bằng email và mật khẩu.  
- **Quản lý tài khoản cá nhân**  
  - Xem, cập nhật thông tin cá nhân, thay đổi avatar.  
- **Mua hàng**  
  - Duyệt danh sách sản phẩm.  
  - Thêm sản phẩm vào giỏ hàng và đặt hàng.  
  - Xem lịch sử giao dịch.  

### 2. **Dành cho quản trị viên (Admin)**  
- **Quản lý sản phẩm**  
  - Thêm, sửa, xóa sản phẩm.  
  - Quản lý danh mục, mô tả, giá cả và hình ảnh sản phẩm.  
- **Quản lý người dùng**  
  - Xem danh sách người dùng.  
  - Gán vai trò (Admin/User) và vô hiệu hóa tài khoản.  
- **Quản lý đơn hàng**  
  - Xem, duyệt, hủy, hoặc cập nhật trạng thái đơn hàng.  

---

## Công nghệ sử dụng

1. **Frontend**  
   - **React Native**: Xây dựng giao diện người dùng đa nền tảng.  
   - **Tailwind CSS**: Thiết kế giao diện nhanh và tối ưu.  
   - **CSS**: Tùy chỉnh chi tiết giao diện.  

2. **Backend**  
   - **Firebase Authentication**: Quản lý xác thực người dùng.  
   - **Firebase Realtime Database**: Lưu trữ dữ liệu người dùng, sản phẩm, và đơn hàng.  
   - **Firebase Storage**: Lưu trữ hình ảnh sản phẩm và avatar người dùng.  

3. **Phân quyền**  
   - Phân quyền giữa **Admin** và **User** trong giao diện và chức năng.
