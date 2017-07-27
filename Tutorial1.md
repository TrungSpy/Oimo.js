#  Part 1: Giới thiệu tổng quan về WebGL

####   WebGL là gì?
1. Có chứa bao hàm các API cho phép Web browser có thể trực tiếp sử dụng tài nguyên GPU của máy tính
2. Hiện tại thì chưa có kĩ thuật nào để gọi thư viện OpenGL từ javascript. Vì vậy sinh ra WebGL như 1 middleware nằm ở giữa javascript và OpenGL có nhiệm vụ 
gọi các hàm của OpenGL
3. WebGL chủ động sử dụng GPU nên xử lí rất nhanh.Tuy nhiên nếu như Web browser có cung cấp những hổ trợ  nhưng phần hardware và OS không hổ trợ thì không thực hiện được.
