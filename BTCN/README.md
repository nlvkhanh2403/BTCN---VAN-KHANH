# BTCN---VAN-KHANH
Bài tập cá nhân - Phát triển ứng dụng TMĐT - Phát triển trang web Cái Lò Nướng

1. Giới thiệu
Đây là bài tập cải tiến giao diện thương mại điện tử dựa trên việc khảo sát website Cái Lò Nướng.

Website mẫu tập trung vào giao diện chi tiết sản phẩm bánh, giúp người dùng xem hình ảnh, thông tin sản phẩm, lựa chọn kích thước, quà tặng kèm, số lượng và thực hiện thao tác thêm sản phẩm vào giỏ hàng.

Phần cải tiến tập trung vào việc sắp xếp lại bố cục và thông tin trên trang chi tiết sản phẩm nhằm giúp giao diện dễ quan sát, rõ ràng và thuận tiện hơn khi mua hàng.

2. Website tham khảo
Tên website: Cái Lò Nướng
URL: https://cailonuong.com/
Khu vực đã khảo sát:
Trang chủ
Danh mục sản phẩm
Chi tiết sản phẩm
Tìm kiếm
Giỏ hàng
Website Cái Lò Nướng cung cấp các sản phẩm như bánh mousse, bánh kem bắp, bánh flan gato, cookie, bánh mì và combo bánh. Các chức năng chính gồm tìm kiếm, duyệt danh mục, xem chi tiết sản phẩm, thêm vào giỏ hàng và đặt hàng.

3. Chức năng
Giao diện được xây dựng với các chức năng chính:

Hiển thị thông tin chi tiết sản phẩm.
Hiển thị hình ảnh và album ảnh sản phẩm.
Hiển thị tên, mô tả và giá sản phẩm.
Lựa chọn kích thước sản phẩm.
Lựa chọn quà tặng kèm.
Điều chỉnh số lượng sản phẩm.
Thêm sản phẩm vào giỏ hàng.
Hiển thị số lượng sản phẩm trong giỏ hàng.
Hiển thị các sản phẩm liên quan.
Bố cục responsive, hỗ trợ nhiều kích thước màn hình.
Lưu ý: Đây là giao diện demo, không sử dụng backend hoặc cơ sở dữ liệu.

4. Công nghệ
HTML5
CSS3
JavaScript cơ bản
HTML được sử dụng để xây dựng cấu trúc trang, CSS dùng để định dạng giao diện và responsive, JavaScript cơ bản được sử dụng cho một số tương tác như chuyển ảnh, thay đổi kích thước bánh, điều chỉnh số lượng và cập nhật số lượng sản phẩm trong giỏ hàng.

5. Cách chạy
Cách 1: Mở trực tiếp bằng trình duyệt
Clone hoặc tải repository về máy.
Mở thư mục dự án.
Mở file index.html bằng trình duyệt.
Có thể sử dụng Chrome hoặc Microsoft Edge để kiểm tra giao diện.
Cách 2: Sử dụng VS Code
Mở thư mục dự án bằng Visual Studio Code.
Mở file index.html.
Chọn Open with Live Server nếu đã cài extension Live Server.
Kiểm tra giao diện trên trình duyệt.
6. Cải tiến đã thực hiện
6.1. Vấn đề ban đầu
Qua quá trình khảo sát, trang chi tiết sản phẩm có lượng thông tin tương đối nhiều và hình ảnh sản phẩm chiếm diện tích lớn. Điều này có thể khiến khách hàng khó quan sát tổng thể và khó xác định nhanh các thông tin quan trọng trước khi mua.

Ngoài ra, phần quà tặng kèm chưa thể hiện thật rõ mối quan hệ với sản phẩm chính.

6.2. Phương án cải tiến
Giao diện được cải tiến theo 3 hướng chính:

Tối ưu bố cục hình ảnh sản phẩm

Sử dụng bố cục hai cột.
Hình ảnh chính được đặt ở khu vực dễ quan sát.
Bổ sung album ảnh và thumbnail để xem nhiều hình ảnh.
Sắp xếp lại thông tin mua hàng

Làm nổi bật tên sản phẩm và giá.
Gom các lựa chọn kích thước vào một khu vực riêng.
Đặt số lượng và nút "Thêm vào giỏ hàng" ở vị trí dễ nhận biết.
Cải thiện khu vực quà tặng kèm

Tách khu vực quà tặng khỏi các thông tin khác.
Hiển thị rõ tên quà tặng và trạng thái miễn phí.
Giúp người dùng dễ hiểu rằng đây là lựa chọn đi kèm sản phẩm chính.
6.3. Điều chỉnh sau khi kiểm tra
Sau khi kiểm tra giao diện trên trình duyệt, em nhận thấy một số hình ảnh sản phẩm chưa phù hợp với sản phẩm được lựa chọn. Vì vậy, em đã chỉnh sửa mã HTML để thay thế các đường dẫn hình ảnh bằng hình ảnh phù hợp hơn.

Ngoài ra, phần nhận diện thương hiệu cũng được rà soát và điều chỉnh để phù hợp với website tham khảo.

Kết quả là giao diện có hình ảnh phù hợp hơn với nội dung sản phẩm và tổng thể trang thống nhất hơn với website tham khảo.

8. Báo cáo kiểm thử
Sau khi hoàn thiện giao diện, em tiến hành kiểm tra lại website trên trình duyệt nhằm đảm bảo các thành phần HTML, CSS và JavaScript hoạt động đúng theo thiết kế. Nội dung kiểm thử tập trung vào giao diện, đường dẫn, hình ảnh, bố cục, khả năng tương tác và khả năng hiển thị trên các kích thước màn hình khác nhau.

8.1. Kiểm tra giao diện và chức năng

Nội dung kiểm thử

Cách kiểm tra

Kết quả

Cấu trúc HTML

Kiểm tra các khu vực Header, Navigation, Breadcrumb, Product Detail, Related Products và Footer có hiển thị đầy đủ hay không.

Đạt

CSS

Kiểm tra file CSS được liên kết với HTML và các thuộc tính CSS được áp dụng đúng vào các thành phần giao diện.

Đạt

Hình ảnh

Kiểm tra hình ảnh sản phẩm chính, thumbnail và các sản phẩm liên quan có hiển thị đúng hay không; kiểm tra lại đường dẫn src.

Đạt

Điều hướng

Kiểm tra các liên kết Trang chủ, Menu Bánh, Liên hệ và Breadcrumb có trỏ đến đúng khu vực trong trang thông qua các id tương ứng.

Đạt

Bố cục Product Card

Kiểm tra các sản phẩm trong phần “Có thể bạn cũng thích” có được sắp xếp thành các cột đồng đều hay không.

Đạt

Gallery sản phẩm

Kiểm tra thumbnail và hai nút chuyển ảnh có thay đổi đúng hình ảnh sản phẩm hay không.

Đạt

Chọn kích thước bánh

Kiểm tra khi chọn size 16 cm hoặc 20 cm, trạng thái lựa chọn và giá sản phẩm có thay đổi tương ứng hay không.

Đạt

Thay đổi số lượng

Kiểm tra nút +, − và ô nhập số lượng; đảm bảo số lượng không nhỏ hơn 1 và không lớn hơn 20.

Đạt

Thêm vào giỏ hàng

Kiểm tra khi nhấn nút “THÊM VÀO GIỎ HÀNG”, số lượng trên biểu tượng giỏ hàng và thông báo xác nhận có được cập nhật hay không.

Đạt

Hover và Focus

Di chuột qua các thành phần tương tác và sử dụng bàn phím để kiểm tra trạng thái :hover và :focus-visible.

Đạt

Responsive

Thu nhỏ và mở rộng cửa sổ trình duyệt để kiểm tra bố cục ở các kích thước màn hình khác nhau.

Đạt

5.2. Vấn đề phát hiện và cách khắc phục

Trong quá trình phát triển, em phát hiện một số điểm cần điều chỉnh trong mã nguồn để giao diện hoạt động và hiển thị đúng hơn.

Vấn đề phát hiện

Cách khắc phục

Một số khai báo CSS trong phiên bản trước sử dụng biến font var(--serif) nhưng biến này chưa được khai báo trong :root.

Kiểm tra lại các biến font và sử dụng các biến đã được khai báo là --display và --sans.

Cần đảm bảo các hình ảnh sản phẩm được liên kết đúng với file hình ảnh trong thư mục dự án.

Kiểm tra lại thuộc tính src của các thẻ <img> và điều chỉnh đường dẫn khi cần thiết.

Cần kiểm tra sự thống nhất giữa các thành phần điều hướng và các khu vực tương ứng trên cùng trang.

Đối chiếu href của các liên kết với id của các khu vực như #top, #related và #footer.

Cần kiểm tra bố cục danh sách sản phẩm khi thay đổi kích thước màn hình.

Sử dụng CSS Grid kết hợp Media Query để điều chỉnh số cột theo kích thước màn hình.

5.3. Kết quả kiểm thử

Sau khi kiểm tra và điều chỉnh, website hiển thị đầy đủ các khu vực chính và các thành phần giao diện hoạt động theo thiết kế. Các chức năng tương tác cơ bản như chuyển ảnh sản phẩm, chọn kích thước bánh, thay đổi số lượng và thêm sản phẩm vào giỏ hàng hoạt động đúng.

Bố cục danh sách sản phẩm được xây dựng bằng CSS Grid và có điều chỉnh responsive thông qua Media Query. Các thành phần tương tác cũng được bổ sung trạng thái hover và focus-visible để cải thiện khả năng sử dụng.
