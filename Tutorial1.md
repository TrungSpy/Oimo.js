#  Part 1: Giới thiệu tổng quan về WebGL

####   WebGL là gì?
1. Có chứa bao hàm các API cho phép Web browser có thể trực tiếp sử dụng tài nguyên GPU của máy tính
2. Hiện tại thì chưa có kĩ thuật nào để gọi thư viện OpenGL từ javascript. Vì vậy sinh ra WebGL như 1 middleware nằm ở giữa javascript và OpenGL có nhiệm vụ 
gọi các hàm của OpenGL
3. WebGL chủ động sử dụng GPU nên xử lí rất nhanh.Tuy nhiên nếu như Web browser có cung cấp những hổ trợ  nhưng phần hardware và OS không hổ trợ thì không thực hiện được.
#### Một vài ví dụ sử dụng WebGL  
1. <a href = "http://www.holoduke.nl/3dbricks/">3dbricks</a>
2. <a href = "http://www.urbangalaxyonline.com/">Urban Galaxy Online</a> 
3. <a href = "https://www.g-star.com/en_nl/newdenimarrivals">G-Star RAW | New Denim Arrivals</a> 
4. <a href = "http://www.fishgl.com/">FishGL</a> 
5. <a href = "http://kile.stravaganza.org/lab/thiswayjs/#">thisway.js by stravaganza</a> 
6. <a href = "http://haxiomic.github.io/projects/webgl-fluid-and-particles/?q=UltraLow">WebGL Fluid Experiment</a>  

#### Điểm mạnh của WebGL  
1.  Nhẹ,dễ dàng chạy ngay lập tức bên trong web browser
2.  Không đòi hỏi nhiều thao tác cài đặt , chỉnh sửa của user
3.  Cung cấp nhiều ứng dụng thực tiễn phong phú
4.  Có thể được kết hợp với các thiết bị công nghệ mới trong tương lai.

