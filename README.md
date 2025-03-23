# HỆ THỐNG QUẢN LÝ SÂN BÓNG

## 1. Giới Thiệu  
Hệ thống quản lý sân bóng giúp nhân viên, quản lý và chủ sân dễ dàng theo dõi và vận hành sân bóng, bao gồm:  
- Quản lý sân bóng và trạng thái sân.  
- Quản lý lịch đặt sân, tránh trùng lịch.  
- Quản lý khách hàng, nhân viên và thanh toán.  
- Báo cáo thống kê doanh thu và tình trạng sân.  

**Lưu ý:** Hệ thống chỉ dành cho nhân viên, khách hàng không thể đặt sân trực tiếp qua hệ thống.  

---

## 2. Tính Năng Chính  

### 2.1. Quản Lý Sân Bóng  
- Danh sách các sân mini và sân lớn.  
- Trạng thái sân: **Trống, Đã đặt, Đang bảo trì**.  
- Hỗ trợ ghép nhiều sân nhỏ thành sân lớn theo yêu cầu.  

### 2.2. Quản Lý Lịch Đặt Sân  
- Nhân viên nhập đặt sân cho khách.  
- Kiểm tra & ngăn chặn đặt trùng lịch.  
- Hiển thị lịch đặt sân theo ngày, tuần, tháng.  
- Hủy hoặc chỉnh sửa lịch đặt khi cần.  

### 2.3. Quản Lý Thanh Toán  
- Hỗ trợ thanh toán qua **Tiền mặt, Chuyển khoản, Momo, QR Code**.  
- Theo dõi đặt cọc & công nợ.  
- Xuất hóa đơn nếu cần.  

### 2.4. Quản Lý Khách Hàng  
- Lưu trữ thông tin khách hàng (**Tên, SĐT, Lịch sử đặt sân**).  
- Ghi chú khách hàng thân thiết hoặc khách hay hủy sân.  

### 2.5. Quản Lý Nhân Viên  
- Phân quyền: **Lễ tân, Quản lý, Kế toán**.  
- Theo dõi lịch sử thao tác của từng nhân viên.  

### 2.6. Báo Cáo & Thống Kê  
- Xem doanh thu theo ngày, tháng.  
- Thống kê lượt đặt sân giúp tối ưu kinh doanh.  
- Báo cáo tình trạng sử dụng sân theo thời gian.
## 3. Chi tiết các tính năng 
### 3.1 Quản lý sân bóng
#### 3.1.1 Danh sách sân bóng 
Hiển thị danh sách tất cả các sân có các thông tin mô tả sau:
- Tên sân
- Loại sân (Mini, Lớn, tiêu chuẩn, cao cấp)
- Kích thước sân
- Giá thuê (theo giờ/buổi/tháng)
- Trạng thái sân (Trống, Đã đặt, Đang bảo trì)
#### 3.1.2 Hiển thị trạng thái sân
Hiển thị trạng thái sân hiện tại:
 - Trống: Có thể đặt sân.
 - Đã đặt: Đã có khách đặt.
 - Đang bảo trì: Không thể đặt.
Nhân viên có thể thay đổi trạng thái sân khi cần.
#### 3.1.3 Ghép sân 
Hỗ trợ ghép 2 hoặc 4 sân mini thành 1 sân lớn khi khách có nhu cầu.

Hệ thống sẽ cập nhật lại trạng thái sân mini để tránh trùng lịch.
#### 3.1.4 Tình trạng sân 
Chất lượng sân
Sân cần bảo trì sửa chữa:
- Sửa chữa gì
- Nâng cấp gì
- Chi phí 
### 3.2 Quản lý lịch đặt sân 
#### 3.2.1 Đặt sân
Nhân viên nhập thông tin đặt sân của khách hàng:
- Thông tin khách hàng: Họ tên, SDT, thông tin cá nhân...
- Sân : Loại sân, kích thước, mô thể thao
- Thời gian: Ngày/tháng/năm, Giờ check in - check out
- Hình thức thuê: theo giờ, ngày, tuần, ...
Kiểm tra tự động tránh trùng lịch
Gửi xác nhận đặt sân qua SMS/Zalo/Messenger/email nếu cần
#### 3.2.2 Quản lý lịch đặt
Hiển thị danh sách lịch đặt sân theo :
- Ngày
- Tuần
- Tháng
- Quỳ
Tìm kiếm lịch đặt theo :
- Tên khách hàng
- Số CCCD/CMTND của khách hàng
- Số điện thoại
#### 3.2.3 Hủy hoặc chỉnh sửa lịch đặt
Nhân viên có thể hủy hoặc thay đổi lịch đặt theo yêu cầu khách hàng hay các tình huống phát sinh
Khi hủy sân, hệ thống sẽ: 
- Cập nhật lại trạng thái sân
- Lưu lý do hủy đặt
- Hoàn hoặc giữ lại tiền đặt cọc ( nếu có)
### 3.3 Quản lý thanh toán 
#### 3.3.1 Ghi nhận thanh toán
Hỗ trợ thanh toán qua các phương thức: 
- Tiền mặt
- Chuyển khoản ngân hàng
- Ví điện tử ( Momo, Zalopay, Viettel money, VNPay, Shopeepay, Apple Pay...)
- Thẻ ( Thẻ tín dụng, thẻ ghi nợ, thẻ ATM...)
Nhân viên nhập số tiền thanh toán và xác nhận
#### 3.3.2 Đặt cọc và Công nợ
Ghi nhận tiền đặt cọc khi khách hàng thuê
Theo dõi công nợ của khách hàng chưa thanh toán đủ
#### 3.3.3 Xuất hóa đơn 
Xuất hóa đơn điện tử theo yêu cầu
In hóa đơn tại quầy hoặc gửi qua email, tin nhắn
### 3.4 Quản lý khách hàng 
#### 3.4.1 Lưu trữ thông tin khách hàng 
Mỗi khách hàng có hồ sơ lưu trữ: 
- Họ tên
- Số điện thoại
- Giấy tờ tùy thân ( số CCCD/Hộ chiếu/CMTND...)
- Lịch sử đặt sân
- Công nợ ( nếu có)
Nhân viên có thể tìm kiếm khách hàng theo số điện thoại hoặc số CCCD/ hộ chiếu...
#### 3.4.2 Khách hàng thân thiết 
Đánh dấu khách hàng thường xuyên để ưu tiên ( phân cấp khách hàng thường xuyên theo chi tiêu của khách hàng cho hệ thống sân và theo số lần đặt sân)
Áp dụng ưu đãi cho khách hàng thân thiết 
#### 3.4.3 Theo dõi hủy sân
Lưu lịch sử hủy sân của khách
Cảnh báo khi khách có tỷ lệ hủy sân cao ( black list)
### 3.5 Quản lý nhân viên 
#### 3.5.1 Phân quyền nhân viên 
Hệ thống có các nhóm quyền truy cập: 
- Nhân viên thường: Quản lý đặt sân, cập nhật trạng thái sân, quản lý khách hàng 
- Quản lý: Quản lý sân, nhân viên, thống kê doanh thu, quản lý thanh toán, công nợ, hóa đơn
- Chủ sân: Thống kê doanh thu, quản lý nhân viên
#### 3.5.2 Theo dõi lịch sử hoạt động
Lưu lại các thao tác của nhân viên: 
- Ai là người đặt sân, hủy sân, thu tiền, phục vụ 
- Thời gian thực hiện thao tác
### 3.6 Báo cáo và thống kê
#### 3.6.1 Báo cáo doanh thu
Hiển thị doanh thu theo: 
- Ngày
- Tuần
- Tháng
- Quý
- Năm
Tổng hợp doanh thu theo :
- loại sân
- Thời gian cao điểm/ thấp điểm
- Hình thức thuê ( giờ/ buổi/ tháng, lẻ/định kì)
### 3.6.2 Báo cáo chi phí ( số tiền chi ra )
Quản lý các khoản chi phí hàng tháng: 
- Tiền điện, nước
- Chi phí bảo trì sân
- Lương nhân viên
- Chi phí nhập hàng cho các dịch vụ khác
- Chi phí quảng cáo và tiếp thị 
Xem báo cáo tổng chi phí theo Ngày/Tháng/Năm
So sánh doanh thu và chi phí để tính lợi nhuận ròng
#### 3.6.3 Thống kê sử dụng sân 
Xem số lần sân được thuê theo thời gian 
Phát hiện giờ cao điểm và thấp điểm đặt sân
#### 3.6.4 Báo cáo tình trạng sân
Xem số lần bảo trì sân 
Phát hiện sân ít được thuê để có thể tối ưu được kinh doanh
## 4.Sơ đồ use case cho từng bộ phận
### 4.1.Use case quản lý sân bóng
*Use Case: Người quản lý 
**Actor (Người thực hiện): Quản lý sân bóng.
-Mục tiêu chính: Quản lý hiệu quả hoạt động của sân bóng thông qua hệ thống.
-Các bước thực hiện:
Đăng nhập: Người quản lý đăng nhập vào hệ thống bằng tài khoản.
-Quản lý sân bóng:
Cập nhật thông tin sân bóng (tên sân, loại sân, trạng thái).
Kiểm tra lịch trống và các lượt đặt sân.
-Quản lý đặt sân:
Xem danh sách các lượt đặt sân.
Phê duyệt hoặc hủy đặt sân nếu cần thiết.
-Quản lý tài chính:
Theo dõi doanh thu từ các lượt đặt sân.
Quản lý hóa đơn và xử lý thanh toán thủ công (nếu có).
-Gửi thông báo:
Thông báo cho khách hàng về thay đổi, khuyến mãi, hoặc hủy đặt sân.
-Báo cáo: Xem các báo cáo tổng hợp về hoạt động, doanh thu, và lượt đặt sân.
-Preconditions (Điều kiện tiên quyết):
Người quản lý đã được cấp tài khoản.
Hệ thống có dữ liệu sân bóng.
-Postconditions (Kết quả):
Thông tin sân và lịch đặt sân được cập nhật.
Doanh thu được thống kê chính xác.
-Các kịch bản phụ:
Người quản lý quên mật khẩu: Sử dụng tính năng “Quên mật khẩu” để khôi phục.
Khách hàng hủy đặt sân: Quản lý xác nhận và cập nhật lại trạng thái.
![alt](http://docs.google.com/document/d/1P9xJ3b6TQ1Q9-gXcF6QlS1FxMi-BcYd2U9LOCRQ6R8k/edit?tab=t.e31fo8dd63me)
### 4.2.Use case của nhân viên
Use Case: Nhân viên hỗ trợ quản lý sân bóng

*Actor (Người thực hiện): Nhân viên.
 -Mục tiêu chính: Hỗ trợ vận hành, xử lý các yêu cầu và đảm bảo trải nghiệm khách hàng.
Các bước thực hiện:

 -Đăng nhập: Nhân viên đăng nhập vào hệ thống với tài khoản của mình.
*Kiểm tra lịch đặt sân:

+Xem danh sách lịch đặt sân theo ngày, tuần, tháng.
+Xác nhận trạng thái sân (đang sử dụng, cần bảo trì)
*Hỗ trợ khách hàng:
Ghi nhận thông tin đặt sân từ khách hàng trực tiếp hoặc qua điện thoại.
Hỗ trợ khách hàng chỉnh sửa hoặc hủy đặt sân.
*Quản lý sân bóng:
Kiểm tra, cập nhật tình trạng sân bóng.
Báo cáo sự cố cần sửa chữa hoặc bảo trì sân
*Xử lý thanh toán:
Hỗ trợ khách hàng thanh toán trực tiếp hoặc qua hệ thống
Xác nhận các khoản tiền thu được và gửi thông tin lên quản lý.
*Gửi thông báo:
Thông báo cho khách hàng về tình trạng sân hoặc các chương trình ưu đãi.
*Preconditions (Điều kiện tiên quyết):
Nhân viên đã được cấp tài khoản và quyền truy cập vào hệ thống.
Hệ thống có dữ liệu cập nhật về sân bóng và lịch đặt sân.
*Postconditions (Kết quả):
Lịch đặt sân và trạng thái sân bóng được cập nhật chính xác.
Khách hàng nhận được hỗ trợ đầy đủ.
*Các kịch bản phụ:
Khách hàng đến đặt sân trực tiếp: Nhân viên nhập thông tin vào hệ thống.
Phát hiện sân cần bảo trì: Nhân viên gửi báo cáo cho quản lý.
![alt](https://docs.google.com/document/d/1P9xJ3b6TQ1Q9-gXcF6QlS1FxMi-BcYd2U9LOCRQ6R8k/edit?tab=t.a6tqoysrmo9u)
### 4.3.Use case quản lý dịch vụ đi kèm
*Use Case: Quản lý dịch vụ đi kèm
*Actor (Người thực hiện): Quản lý hoặc nhân viên.
*Mục tiêu chính: Quản lý hiệu quả các dịch vụ bổ sung nhằm phục vụ khách hàng (như cho thuê bóng, áo đấu, nước uống, v.v.).
*Luồng chính (Main Flow):
-Đăng nhập:
Quản lý/nhân viên đăng nhập vào hệ thống bằng tài khoản có quyền truy cập.
-Cập nhật danh sách dịch vụ:
Thêm dịch vụ mới (tên, mô tả, giá cả, trạng thái).
Chỉnh sửa thông tin dịch vụ hiện tại (ví dụ: cập nhật giá hoặc trạng thái còn/hết hàng).
Xóa dịch vụ không còn cung cấp.
-Quản lý tồn kho (nếu có):
Kiểm tra số lượng tồn kho của các dịch vụ (như bóng, áo đấu, khăn).
Cập nhật số lượng khi nhập thêm hoặc khi dịch vụ được sử dụng.
-Xử lý yêu cầu dịch vụ:
Ghi nhận yêu cầu dịch vụ từ khách hàng.
Cập nhật hóa đơn kèm theo dịch vụ đi kèm.
-Báo cáo và thống kê:
Xem báo cáo doanh thu từ các dịch vụ đi kèm.
Theo dõi lịch sử sử dụng dịch vụ để tối ưu hóa việc cung cấp.
*Điều kiện tiên quyết (Preconditions):
Tài khoản quản lý hoặc nhân viên có quyền truy cập chức năng dịch vụ đi kèm.
Dịch vụ đã được thiết lập trong hệ thống.
*Kết quả (Postconditions):
+Thông tin dịch vụ được cập nhật chính xác.
+Yêu cầu dịch vụ của khách hàng được xử lý đầy đủ.
+Doanh thu từ dịch vụ đi kèm được thống kê.
*Các kịch bản phụ (Alternate Scenarios):
Dịch vụ hết hàng:
+Hệ thống thông báo dịch vụ không khả dụng, yêu cầu cập nhật tồn kho.
*Khách hàng thay đổi yêu cầu:
+Nhân viên chỉnh sửa hóa đơn để phản ánh thay đổi.
![alt](https://docs.google.com/document/d/1P9xJ3b6TQ1Q9-gXcF6QlS1FxMi-BcYd2U9LOCRQ6R8k/edit?tab=t.4v1uuacfodhu)










