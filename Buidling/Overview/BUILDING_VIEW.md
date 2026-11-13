QUẢN LÝ TÒA NHÀ – ROOMFORRENT SYSTEM
=====================================

MỤC ĐÍCH VIEW: Quản lý toàn bộ tòa nhà, phòng trống, giá thuê,
tiền cọc, phí quản lý, nội thất, tài chính và booking.

---------------------------------------------------------------------
1. THÔNG TIN TÒA NHÀ (từ SƠ ĐỒ CÁC TÒA NHÀ + SẢN PHẨM NGOÀI)
- Tên tòa nhà, địa chỉ: Tân Phú - Hồ Chí Minh.
- Các cột dữ liệu quan trọng: SẮP TRỐNG; ĐÃ BLOCK; PHÒNG TRỐNG; LÀM HỢP ĐỒNG; GIÁ THUÊ;
  NGÀY NHẬN; KIỂU PHÒNG; GHI CHÚ; XE MÁY; TÀI CHÍNH; PHÍ DỊCH VỤ; PHÍ QUẢN LÝ (300K/PHÒNG);
  ĐIỆN (4K/SỐ); NƯỚC (30K/KHỐI); XE MÁY MIỆN PHÍ ĐỂ XE; QUẢN LÝ (100K/NGƯỜI); NỘI THẤT CÓ SẴN.
- Nội thất trong phòng: TỦ LẠNH; MÁY GIẶT + SẤY (TUỲ PHÒNG); MÁY LẠNH; TỦ GIÀY; BÀN HỌC;
  GIƯỜNG (1m8x2m); NỀM; TỦ BẾP TRÊN/DƯỚI; BÀN GHẾ ĂN; TẦNG 5; HÚT MÙI; SOFA (1m6);
  TỦ QUẦN ÁO (1m8); BÀN GHẾ ĂN; TẦNG 4; LINK ẢNH PHÒNG MẪU; TỔNG QUAN TIỆN ÍCH; VIEW PHÒNG;
  THANG MÁY; THANG BỘ; HÀNH LANG; KHÔNG GIỜI HẠN NGƯỜI Ở; QUY ĐỊNH BẮT BUỘC; THANG BỘ;
  NỘI THẤT BỔ SUNG.

---------------------------------------------------------------------
2. DANH SÁCH PHÒNG VỚI GIÁ (từ SẢN PHẨM NGOÀI / SƠ ĐỒ)
- MB: 14.000.000; P101: 5.000.000; P102: 3.800.000; P103: 3.800.000; P201: 4.300.000;
  P202: 4.000.000; P203: 4.300.000; P301: 4.300.000; P302: 4.200.000; P303: 4.300.000;
  P401: 4.300.000; P402: 4.200.000; P403: 4.300.000; P404: 4.300.000; P406: 4.300.000;
  P408: 4.300.000; P501: 4.300.000; P502: 4.200.000; P503: 4.300.000; P601: 5.800.000;
  P602: 6.000.000.

---------------------------------------------------------------------
3. SƠ ĐỒ / BẢN VẤT TẦNG – GIÁ PHÒNG (từ BỘ BUILDING A / BUILDING B)
- P305: 7.800.000 đ; P304: 6.800.000 đ; P303: 6.200.000 đ; P302: 7.200.000 đ; P301: 7.800.000 đ;
  P205: 7.800.000 đ; P204: 6.800.000 đ; P203: 6.200.000 đ; P105: 7.200.000 đ; P104: 6.800.000 đ;
  P103: 5.500.000 đ; P201: 8.000.000 đ (Ban công rộng); P202: 7.000.000 đ.

---------------------------------------------------------------------
4. PHÒNG – TRẠNG THÁI VÀ CỌC
- Trạng thái: TRỐNG, ĐÃ BLOCK, ĐẶT CỌC, CHỜ HĐ, BẢO TRÌ.
- Cọc: CHỈ NHẬN CỌC 1,5 THÁNG; CỌC 1 THÁNG; CỌC GIỮ CHỖ TỐI THIỂU 2.000.000 Đ BỔ SUNG SAU 3 NGÀY;
  LÀM HỢP ĐỒNG SAU 7 NGÀY KỂ TỪ NGÀY PHÁT SINH CỌC.

---------------------------------------------------------------------
5. BOOKING / TÀI CHÍNH THUÊ (từ DOANH SỐ THÁM THUÊ)
- Booking ví dụ: P206 - PĐG 2 - PĐG 2 - P206; P103 - PĐG 2; PS002 - 131HVL; PS406 - 131HVL;
  P007 - 175HVL 175HVL - P007; P406 - PA; P403 - PA; P002 - 115LK45; P105 - NTT; PS408 - 131HVL;
  P001 - NTT; P206 - PĐG 2; P110 - 11BT; P206 - PĐG; P412 - PA; P312 - 85BT; P407 - PĐG 2;
  P005 - 175HVL; P107 - 175HVL; P106 - PA; P504 - PA; P209 - PA; P103 - 423AC 423AC - P103;
  P310 - 115LK45; P509 - 115LK45.

---------------------------------------------------------------------
6. YÊU CẦU VIEW
- CRUD tòa nhà; phòng; giá; cọc; phí QL; tài chính; booking; thiết bị.

- Yêu cầu UI mới (đang triển khai trong BUILDING.html):
  - Làm cho giao diện quản lý tòa nhà gọn, dễ dùng (bớt nhiễu, tối ưu màn hình).
  - Đã triển khai: stats + bảng danh sách tòa nhà duy nhất (Tên tòa nhà | Địa chỉ | Số tầng |
    Số phòng | Sắp trống | Đã block | Đã đặt) + nút “+ Tạo tòa nhà mới” trong bảng danh sách.
  - Bản vẽ SVG “Sơ đồ tòa nhà / Phòng” sau đó đã được gỡ khỏi view Quản lý Tòa nhà.

---------------------------------------------------------------------
7. THỜI GIAN: SỐ PHÒNG THEO TRẠNG THÁI – ÁP DỤNG CHO QUẢN LÝ TÒA NHÀ
- Yêu cầu: Thêm số phòng theo 3 trạng thái: Sắp trống, Đã block, Đã đặt (chờ hợp đồng).
- Yêu cầu: Chỉ nên là 1 table – gộp số phòng theo trạng thái vào bảng danh sách tòa nhà
  (Tên tòa nhà | Địa chỉ | Số tầng | Số phòng | Sắp trống | Đã block | Đã đặt).
- Yêu cầu: Có nút “+ Tạo tòa nhà mới” trong view Quản lý Tòa nhà (nằm trên bảng danh sách tòa nhà).
- Áp dụng cho: Danh sách tòa nhà / Quản lý tòa nhà.
- Trạng thái được lấy từ dữ liệu tòa nhà/phòng trong file SƠ ĐỒ CÁC TÒA NHÀ + SẢN PHẨM NGOÀI.

---------------------------------------------------------------------
8. TÀI LIỆU VẼ – BUILDING.html
- File HTML: Buidling/Overview/BUILDING.html
- Dùng Tailwind CSS (CDN) + sidebar + bảng danh sách tòa nhà + stats (đã gỡ sơ đồ tầng/phòng).
- Mỗi lần sửa: cập nhật đồng bộ txt + html + feature list.

---------------------------------------------------------------------
9. VIEW CHI TIẾT TÒA NHÀ – BUILDING_DETAIL.HTML
- File HTML: Buidling/Detail/BUILDING_DETAIL.html
- Mục đích: xem chi tiết một tòa nhà (tên + địa chỉ, số tầng, tổng phòng, trạng thái phòng).
- Nội dung: thông tin tòa nhà (tên, địa chỉ, số tầng, hoa hồng CLB, chủ nhà/SĐĐ, phí QL, điện, nước, quản lý, cọc, wifi user/pass, tiện ích miễn phí, nội thất mặc định); chính sách tòa nhà; stats theo trạng thái; danh sách phòng + giá.
- Thông tin tòa nhà & chính sách tòa nhà: có nút “Sửa” để chỉnh sửa được thông tin và chính sách.
- Form sửa “Thông tin tòa nhà” khớp với nội dung hiển thị: tên, địa chỉ, số tầng, hoa hồng, chủ nhà/SĐĐ, phí quản lý, điện, nước, quản lý, cọc (tháng), wifi user/pass, tiện ích (chọn từ danh sách checkbox), nội thất có sẵn (chọn từ danh sách checkbox).
- Tiện ích tòa nhà & nội thất có sẵn được hiển thị dạng chips/badge (emerald cho tiện ích, amber cho nội thất), không phải dòng chữ đơn.
- Danh sách phòng: có nút hành động từng dòng (thêm phép phép faceId/fingerId, thêm khách mới, đổi trạng thái, thêm nội thất, Setting) và hàng loạt (thêm nội thất, đổi trạng thái).
- Tooltip hợp đồng khi hover dòng phòng (`roomHoverTip`): hiển thị thông tin khách thuê hiện tại gồm
  - danh sách khách thuê (tên, SĐT, vai trò Đại diện / Ở cùng),
  - danh sách thiết bị / xe máy (biển số + dòng xe),
  - thời hạn hợp đồng: ngày HĐ và ngày hết hạn, kèm số ngày còn lại / cảnh báo “Sắp hết hạn” (≤ 30 ngày) hoặc “Đã hết hạn”;
  - phòng đặt cọc chưa ký HĐ hiển thị “Chưa ký hợp đồng (khách đặt cọc)” + ngày dự kiến vào/hết hạn;
  - phòng không có hợp đồng hiển thị “Chưa có hợp đồng – chưa có khách thuê”.
  - Tooltip dùng `position: fixed` (không bị cắt bởi khung cuộn bảng), tự né mép phải/dưới màn hình, ẩn khi rời dòng hoặc cuộn trang; phòng có hợp đồng có icon ⓘ cạnh mã phòng.
- Toolbar danh sách phòng: ô tìm kiếm theo mã phòng; nút “Bộ lọc” mở popup lọc theo tầng / khoảng giá / trạng thái / nhiều nội thất (có badge số bộ lọc đang áp dụng); nút 3 chấm (⋮) chứa danh sách công cụ hàng loạt dạng icon + tên.
- Nút “Setting” mỗi dòng phòng: chỉ thêm nút, chưa thiết kế – quy trình setting phòng sẽ làm ở file khác (handler hiện là no-op).
- Chọn nhiều phòng bằng checkbox ở cột “Chọn” -> mở menu 3 chấm -> chọn công cụ hàng loạt -> popup điều chỉnh giá trị -> nhấn OK/Cancel.
- Phân trang danh sách phòng (`roomPagination`): chọn số dòng/trang (5/10/20/50), hiển thị “Hiển thị a–b / N phòng”, nút Trước/Sau + số trang; tự reset về trang 1 khi đổi tòa nhà, tìm kiếm hoặc áp dụng/xóa bộ lọc.
- Sơ đồ tầng/phòng (SVG) không còn hiển thị trong view chi tiết.
- Chọn tòa nhà: dropdown `detailBuildingSelect` trong view chi tiết, hoặc query `?building=A|B` trên URL.
- Nút “⚙ Cấu hình phòng” (`btnRoomConfig`) ở header view chi tiết → mở `../Config/ROOM_CONFIG.html?building=<id tòa đang chọn>`; href tự cập nhật khi đổi tòa nhà.

---------------------------------------------------------------------
10. VIEW TẠO TÒA NHÀ – CREATE_BUILDING.HTML
- File HTML: Buidling/Create/CREATE_BUILDING.html
- Mở từ nút “+ Tạo tòa nhà mới” ở BUILDING.html (link `../Create/CREATE_BUILDING.html`).
- Form là wizard 2 bước (stepper đầu trang):
  - Bước 1 – Thông tin tòa nhà (các nhóm khớp view chi tiết):
    - Thông tin cơ bản: tên tòa nhà*, địa chỉ*, số tầng*, hoa hồng %, chủ nhà, SĐĐ chủ.
    - Chi phí – Cọc – Wifi: phí quản lý, điện, nước, quản lý/người, cọc (tháng), wifi user/pass.
    - TIỆN ÍCH TÒA NHÀ: MIỄN PHÍ (checkbox chips, mặc định chọn sẵn 6 tiện ích).
    - NỘI THẤT CÓ SẴN MIỄN PHÍ SỬ DỤNG (checkbox chips, mặc định chọn sẵn 5 nội thất).
    - Chính sách tòa nhà: nhận cọc tối đa, cọc đầu tháng, cọc giữ chỗ tối thiểu, số ngày bổ sung cọc, hợp đồng sau N ngày, xe máy miễn phí, tối đa xe/phòng.
    - Ghi chú nội bộ.
  - Bước 2 – Tầng & Phòng (luồng giống tạo sản phẩm trên Shopee):
    - Khối “Thêm tầng”: nhập tầng*, số phòng*, giá thuê mặc định, diện tích mặc định → nút “+ Tạo tầng”. Hệ thống tự sinh danh sách phòng cho tầng đó (mã P101, P102… theo tầng, giá/diện tích/nội thất lấy theo mặc định của tầng).
    - Validate tầng: tầng >= 1, không trùng tầng đã tạo, số phòng >= 1; lỗi hiển thị ngay dưới khối thêm tầng.
    - Mỗi tầng là một card riêng: tiêu đề “Tầng N” + badge số phòng; dòng “Mặc định tầng” gồm ô giá thuê, ô diện tích và nút “Áp dụng cho tất cả phòng” (cập nhật giá/diện tích cho mọi phòng của tầng, có confirm); các nút “+ Thêm phòng”, “Xóa tầng” (xóa tầng kèm toàn bộ phòng, có confirm).
    - Bảng phòng trong tầng: cột Chọn (checkbox), mã phòng, giá thuê, diện tích, chỉ số điện, chỉ số nước, kiểu phòng, nội thất, ghi chú, hành động Sửa/Xóa.
    - Sửa từng phòng qua modal: mã phòng mặc định*, giá thuê*, diện tích (m²), chỉ số điện ban đầu, chỉ số nước ban đầu, kiểu phòng (chọn nhiều: Tách bếp, Ban công, 1PN, 2PN, 3PN, CS trời, Duplex), nội thất (chọn nhiều), ghi chú.
    - Validate phòng: bắt buộc mã phòng, mã không trùng trong toàn tòa nhà, giá thuê >= 0; lỗi hiển thị đầu modal.
    - Đặt giá trị hàng loạt: chọn nhiều phòng bằng checkbox (hoặc “Chọn tất cả phòng”) → nút “⚙ Đặt giá trị hàng loạt” → modal cho phép bật/tắt từng trường (giá thuê, diện tích, chỉ số điện, chỉ số nước, kiểu phòng, nội thất, ghi chú) rồi “Áp dụng”; phải chọn ít nhất 1 trường.
    - Nội thất của phòng mới (do tầng sinh ra hoặc thêm tay) mặc định lấy theo nội thất đã chọn ở bước 1.
    - Có thể bỏ trống danh sách tầng/phòng và bổ sung sau.
- Sidebar phải: “Tóm tắt” cập nhật trực tiếp (tên, địa chỉ, số tầng, tầng đã tạo, phòng đã tạo, hoa hồng, cọc, phí, điện/nước, số tiện ích/nội thất); nút “Tiếp tục →” ở bước 1, “Tạo tòa nhà” + “← Quay lại bước 1” ở bước 2, kèm “Hủy”.
- Validate bước 1: bắt buộc tên + địa chỉ, số tầng > 0, hoa hồng 0–100; lỗi hiển thị dưới từng trường.
- Sau khi tạo: hiện popup “Tạo tòa nhà thành công” (thông tin tóm tắt + số phòng đã tạo) với nút “Tạo tòa nhà khác” hoặc “Về danh sách”. Payload (gồm `rooms` với types/furnishings/chỉ số điện nước) cũng được `console.log` để kiểm tra.
- Dữ liệu minh hoạ – chưa kết nối backend (không ghi vào BUILDING.html).

---------------------------------------------------------------------
11. VIEW CẤU HÌNH PHÒNG – ROOM_CONFIG.HTML
- File HTML: Buidling/Config/ROOM_CONFIG.html
- Mở từ nút “⚙ Cấu hình phòng” ở BUILDING_DETAIL.html: `../Config/ROOM_CONFIG.html?building=A|B`.
- Đây chính là **bước 2 (Tầng & Phòng) của luồng tạo tòa nhà**, nhưng nạp sẵn dữ liệu phòng hiện có của tòa nhà đang chọn:
  - Tầng được suy ra từ danh sách phòng hiện có; mỗi tầng là card “Tầng N” + badge số phòng.
  - Bảng phòng giữ nguyên cột như bước 2: Chọn | Mã phòng | Giá thuê | Diện tích | Chỉ số điện | Chỉ số nước | Kiểu phòng | Nội thất | Ghi chú | Hành động.
  - Mã phòng có chấm màu trạng thái (xanh Sắp trống, tím Đang thuê, vàng Đặt cọc/Chờ HĐ, xanh dương Bảo trì, đỏ Đã block) để tránh sửa/xóa nhầm phòng đang có khách.
- Giữ nguyên các thao tác của bước 2:
  - “Thêm tầng” (tầng*, số phòng*, giá/diện tích mặc định) – báo lỗi nếu tầng đã tồn tại.
  - Mỗi tầng: ô “Mặc định tầng” (giá, diện tích) + “Áp dụng cho tất cả phòng”, “+ Thêm phòng”, “Xóa tầng” (cảnh báo nếu tầng có phòng đang thuê/đặt cọc).
  - Modal sửa/thêm phòng: mã phòng*, giá thuê*, diện tích, chỉ số điện/nước, kiểu phòng (multi-select), nội thất (multi-select), ghi chú; validate mã không trùng trong tòa nhà, giá >= 0.
  - Chọn nhiều phòng bằng checkbox / “Chọn tất cả phòng” → “⚙ Đặt giá trị hàng loạt” → modal bật/tắt từng trường → “Áp dụng”.
  - Xóa phòng đang thuê/đặt cọc phải xác nhận.
- Header: tên tòa nhà + địa chỉ, dropdown đổi tòa nhà (chuyển trang, cảnh báo nếu có thay đổi chưa lưu), link “← Chi tiết tòa nhà”.
- Stats: số tầng, tổng phòng, giá thuê trung bình, số phòng đang thuê/đặt cọc.
- Sidebar phải “Tóm tắt cấu hình”: tòa nhà, địa chỉ, số tầng, tổng phòng, đang thuê/đặt cọc, giá TB, phòng đã chọn + nút “Lưu cấu hình phòng” / “Hủy”, kèm dòng nhắc “Có thay đổi chưa lưu.”.
- Lưu: hiện popup xác nhận (số tầng, tổng phòng, phòng thêm mới/đã xóa) với nút “Tiếp tục chỉnh sửa” hoặc “Về chi tiết tòa nhà”; payload (`rooms[]` giữ `status`, `deposit`, types/furnishings) được `console.log`.
- Hủy / đổi tòa nhà khi có thay đổi chưa lưu → confirm trước khi rời trang. ESC đóng modal đang mở.
- Dữ liệu minh hoạ – chưa kết nối backend (thay đổi không ghi ngược vào BUILDING_DETAIL.html).

---------------------------------------------------------------------
12. FEATURE LIST – QUẢN LÝ TÒA NHÀ (BUILDING)
- [x] CRUD tòa nhà.
- [x] Tạo tòa nhà mới (Buidling/Create/CREATE_BUILDING.html): wizard 2 bước – bước 1 thông tin + chính sách + tiện ích/nội thất (chọn từ danh sách); bước 2 thêm tầng (số tầng + số phòng + giá/diện tích mặc định) để tự sinh danh sách phòng, sửa từng phòng (mã, giá, diện tích, chỉ số điện/nước, kiểu phòng, nội thất, ghi chú) và đặt giá trị hàng loạt cho các phòng đã chọn; có tóm tắt trực tiếp, validate và popup xác nhận.
- [x] Phân trang danh sách tòa nhà (`buildingPagination`): số dòng/trang (5/10/20/50), “Hiển thị a–b / N tòa nhà”, Trước/Sau + số trang.
- [x] Xem chi tiết tòa nhà (BUILDING_DETAIL.html) – gồm dropdown chọn tòa, stats, thông tin + chính sách (có nút sửa), danh sách phòng + nút hành động (từng dòng/hàng loạt), tooltip hợp đồng khi hover dòng phòng (khách thuê, thiết bị/xe máy, ngày HĐ & ngày hết hạn). Sơ đồ SVG đã gỡ.
- [x] Cấu hình phòng (Buidling/Config/ROOM_CONFIG.html): mở từ nút “⚙ Cấu hình phòng” ở view chi tiết, dùng lại đúng UI bước 2 của luồng tạo (thêm tầng, sinh phòng, sửa từng phòng, đặt giá trị hàng loạt) nhưng nạp sẵn dữ liệu phòng hiện có của tòa nhà; có chấm màu trạng thái, cảnh báo khi xóa phòng/tầng đang thuê, lưu bằng popup xác nhận.
- [ ] Sơ đồ tầng/phòng (đã gỡ khỏi view Quản lý Tòa nhà – BUILDING.html).
- [ ] Phòng.
- [ ] Giá.
- [ ] Cọc.
- [ ] Phí quản lý.
- [ ] Tài chính.
- [ ] Booking.
- [ ] Thiết bị.

---------------------------------------------------------------------
13. KẾT LUẬN
- View Quản lý Tòa nhà cần đầy đủ: thông tin tòa nhà, danh sách phòng + giá,
  trạng thái/cọc, tài chính/booking, thiết bị.
- View hiện tại đã đạt: thông tin tòa nhà, danh sách phòng + giá, trạng thái/cọc,
  tài chính/booking, thiết bị (từ dữ liệu file Excel).
