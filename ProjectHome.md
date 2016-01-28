1. Mô tả bài toán
> Đào tạo theo qui chế tín chỉ là một loại hình quản lý đào tạo có nhiều ưu điểm và mang lại hiệu quả cao. Điều này đã được thực tiễn của nhiều nước chứng minh, và hiện nay hầu hết các nước tiên tiến đều áp dụng quản lý đào tạo theo quy chế tín chỉ. Trường Đại học Cần Thơ (ĐHCT) áp dụng học chế tín chỉ. Nguyên tắc đào tạo theo học chế tín chỉ là cách quản lý đào tạo một cách mềm dẻo giúp sinh viên thực hiện việc học tập một cách linh động, có thể tự xây dựng kế hoạch học tập phù hợp với hoàn cảnh cụ thể của từng cá nhân. Với nhu cầu tin học hóa khâu lập kế hoạch học tập (KHHT) và đăng ký môn học (ĐKMH); do đó, nhà trường cần xây dựng hệ thống quản lý đáp ứng các yêu cầu trên.
Mỗi sinh viên theo học tại trường sẽ được quản lý thông qua mã sinh viên, họ tên, ngày tháng năm sinh, địa chỉ,…Mã số sinh viên là cơ sở để phân biệt 2 sinh viên với nhau, để đăng nhập vào hệ thống, sinh viên được cung cấp 1 tài khoản gồm tên đăng nhập và mật khẩu.
Trường gồm nhiều khoa trực thuộc, một sinh viên thuộc 1 lớp học, lớp học thuộc một chuyên ngành cụ thể nào đó; chuyên ngành lại thuộc một khoa. Mỗi một chuyên ngành có một chương trình đào tạo riêng và có thể khác nhau theo từng khóa; chương trình đào tạo là tập hợp những học phần mà sinh viên phải hoàn thành. Học phần hay còn gọi là môn học bao gồm mã học phần, tên học phần, số tín chỉ học phần, mã học phần là duy nhất; một học phần có hoặc không có học phần tiên quyết.
Trên cơ sở khung chương trình đào tạo của từng ngành, mỗi sinh viên xây dựng KHHT toàn khóa sao cho phù hợp với thời gian của mỗi sinh viên. KHHT toàn khóa phải đầy đủ thông tin cá nhân của sinh viên, phải có mã học phần, tên học phần, số tín chỉ tương ứng với từng học phần, học kỳ, niên khóa, … Đầu khóa học, sinh viên phải lập KHHT toàn khóa nhằm làm cơ sở cho việc tổ chức lớp học của trường sau này. Trong lần lập kế hoạch này, hệ thống sẽ kiểm tra số tín chỉ tổng cộng của toàn khóa học và học phần tiên quyết. Tín chỉ tối đa cho mỗi học kỳ chính là 20 tín chỉ và học kỳ hè là 8.
Trước khi bắt đầu học kỳ mới, nhà trường sẽ dựa vào KHHT để mở lớp học phần và công bố kế hoạch giảng dạy, học phần mở trong học kỳ cho sinh viên theo dõi . Một học phần được mở sẽ có một hoặc nhiều nhóm học phần được sắp xếp trong 1 file excel bao gồm CBGD, tuần, thứ, tiết … và được công bố rộng rãi cho sinh viên.
Sau khi lập KHHT, cố vấn sẽ duyệt KHHT của sinh viên; tại mỗi học kỳ, sinh viên chỉ được đăng ký những môn đúng trong KHHT và đã được duyệt. ĐKMH là thao tác sinh viên tự lập cho mình một thời khóa biểu, sinh viên không được đăng ký học 2 nhóm cùng một ngày, cùng tiết học.
Đây là hệ thống quản lý việc lập KHHT và ĐKMH của sinh viên. Ngoài việc cho phép sinh viên lập KHHT và ĐKMH, hệ thống không đề cập đến bất cứ vấn đề gì liên quan đến quản lý nhân sự trong nhà trường, cũng như là việc quản lý sinh viên, bố trí phòng ốc giảng dạy hay phân công sắp xếp thời khóa biểu cho các nhóm học.

2. Yêu cầu của hệ thống:
Hệ thống gồm có các chức năng sau:
-  Import khung chương trình đào tạo từ file excel có sẵn.
-  Import học phần mở trong học kỳ.
- Cho phép sinh viên lập kế hoạch học tập của mình (tối đa 20 tín chỉ trong một học kỳ chính, 8 tín chỉ trong học kỳ hè). Hệ thống sẽ kiểm tra các môn tiên quyết nếu có.
- Hệ thống cung cấp chức năng cho giảng viên duyệt kế hoạch học tập của sinh viên.
- Cho phép sinh viên đăng ký môn học tại mỗi học kỳ và in kết quả đã đăng ký.

3. Hướng giải quyết, môi trường cài đặt và kế hoạch thực hiện:
Hướng giải quyết của bài toán được thực hiện qua các giai đoạn:
	Phân tích: Tìm hiểu vấn đề, yêu cầu bài toán để đưa ra hướng giải quyết.
	Thiết kế: Thiết kế giao diện hệ thống, xây dựng các câu truy vấn để giải quyết được yêu cầu bài toán, xây dựng CSDL.
	Xây dựng: Sử dụng ngôn ngữ lập trình, công cụ phát triển để giải quyết bài toán.
	Phát triển: Kiểm thử để hoàn chỉnh sản phẩm.