# Hướng dẫn học có hệ thống về phát triển Android OpenGLES 3.0

[! [Giấy phép] (https://img.shields.io/badge/License-Apache%202.0-blue.svg)] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/LICENSE.txt)
! [Xây dựng] (https://img.shields.io/badge/build-passing-brightgreen)
[! [apk] (https://img.shields.io/badge/APK-download-green.svg)] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/raw/master/doc/OepnGLES.apk)


Lưu ý: Vui lòng sử dụng Android Studio 4.1+, NDK r21, một số hiệu ứng 3D của Ốp lưng được kích hoạt bằng cử chỉ (xoay và thu phóng)


## kế hoạch


! [beat_heart] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/beating_heart.gif)
! [poly_3d_model] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/poly.gif)

! [ogl_head] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/head.gif)


## Khái niệm cơ bản

- [Phát triển OpenGL ES 3.0 (01): Vẽ hình tam giác] (https://blog.csdn.net/Kennethdroid/article/details/95622391)

- [Phát triển OpenGL ES 3.0 (02): Bản đồ kết cấu] (https://blog.csdn.net/Kennethdroid/article/details/96887637)

- [Phát triển OpenGL ES 3.0 (03): Kết xuất YUV] (https://blog.csdn.net/Kennethdroid/article/details/97153407)

- [Phát triển OpenGL ES 3.0 (04): VBO, EBO và VAO] (https://blog.csdn.net/Kennethdroid/article/details/98088890)

- [Phát triển OpenGL ES 3.0 (05): Kết xuất ngoài màn hình FBO] (https://blog.csdn.net/Kennethdroid/article/details/98883854)

- [Phát triển OpenGL ES 3.0 (06): EGL] (https://blog.csdn.net/Kennethdroid/article/details/99655635)

- [Phát triển OpenGL ES 3.0 (07): Phản hồi chuyển đổi] (https://blog.csdn.net/Kennethdroid/article/details/100083599)

- [Phát triển OpenGL ES 3.0 (08): Hệ tọa độ] (https://blog.csdn.net/Kennethdroid/article/details/100898155)

- [Phát triển OpenGL ES 3.0 (09): Kiến thức cơ bản về ánh sáng] (https://blog.csdn.net/Kennethdroid/article/details/101220947)

- [Phát triển OpenGL ES 3.0 (10): Kiểm tra độ sâu] (https://blog.csdn.net/Kennethdroid/article/details/101709694)

- [Phát triển OpenGL ES 3.0 (11): Kiểm tra mẫu] (https://blog.csdn.net/Kennethdroid/article/details/102533260)

- [Phát triển OpenGL ES 3.0 (12): Kết hợp] (https://blog.csdn.net/Kennethdroid/article/details/102630858)

- [OpenGL ES 3.0 Development (13): Instancing] (https://blog.csdn.net/Kennethdroid/article/details/102770813)

- [Phát triển OpenGL ES 3.0 (14): Hạt] (https://blog.csdn.net/Kennethdroid/article/details/102881654)

- [Phát triển OpenGL ES 3.0 (15): Cubemap (Skybox)] (https://blog.csdn.net/Kennethdroid/article/details/102991524)

- [Phát triển OpenGL ES 3.0 (16): Xem trước máy ảnh] (https://blog.csdn.net/Kennethdroid/article/details/103189489)

- [OpenGL ES 3.0 Development (17): Camera Basic Filters] (https://blog.csdn.net/Kennethdroid/article/details/103335598)

- [OpenGL ES 3.0 Development (18): Camera LUT Filter] (https://blog.csdn.net/Kennethdroid/article/details/103355129)

- [Phát triển OpenGL ES 3.0 (19): bộ lọc rung máy ảnh] (https://blog.csdn.net/Kennethdroid/article/details/103449935)

- [Phát triển OpenGL ES 3.0 (20): Mô hình 3D] (https://blog.csdn.net/Kennethdroid/article/details/103771970)

- [Phát triển OpenGL ES 3.0 (21): Tải và hiển thị mô hình 3D] (https://blog.csdn.net/Kennethdroid/article/details/103825593)

- [Phát triển OpenGL ES 3.0 (22): PBO] (https://blog.csdn.net/Kennethdroid/article/details/103931627)

- [Phát triển OpenGL ES 3.0 (23): Nhiều mục tiêu kết xuất (MRT)] (https://blog.csdn.net/Kennethdroid/article/details/108873665)

- [Phát triển OpenGL ES 3.0 (24): Truyền khối bit bộ đệm khung (Blit)] (https://blog.csdn.net/Kennethdroid/article/details/109032497)

- [Phát triển OpenGL ES 3.0 (25): TBO (GLES 3.1)] (https://blog.csdn.net/Kennethdroid/article/details/109749018)

- [Phát triển OpenGL ES 3.0 (26): UBO (GLES 3.2)] (https://blog.csdn.net/Kennethdroid/article/details/109749018)


## kế hoạch

! [avatar] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/avatar.gif)
! [board] (https://github.com/githubhaohao/NDK_OpenGLES_3_0/blob/master/gif/draw_board.gif)

## Đơn xin

- [Android OpenGL ES nhận ra các hiệu ứng đặc biệt khiến tim đập mạnh] (https://blog.csdn.net/Kennethdroid/article/details/104536532)

- [Android OpenGL ES nhận ra tác dụng của việc giảm béo và dài chân] (https://blog.csdn.net/Kennethdroid/article/details/104546234)

- [Android OpenGL ES vẽ đường cong Bezier] (https://blog.csdn.net/Kennethdroid/article/details/104721096)

- [Android OpenGL ES nhận ra hiệu ứng của khuôn mặt gầy và đôi mắt to] (https://blog.csdn.net/Kennethdroid/article/details/104907763)

- [Android OpenGL ES nhận ra biến dạng đầu và hiệu ứng lắc đầu] (https://blog.csdn.net/Kennethdroid/article/details/105208054)

- [Android OpenGL ES hiện thực hóa hình ảnh của âm thanh thời gian thực] (https://blog.csdn.net/Kennethdroid/article/details/106128767)

- [Android OpenGL ES triển khai chức năng thẻ cào và máy tính bảng] (https://blog.csdn.net/Kennethdroid/article/details/106339286)

- [Android OpenGL ES triển khai hiệu ứng Hình đại diện 3D] (https://blog.csdn.net/Kennethdroid/article/details/106423475)

- [Android OpenGL ES nhận ra hiệu ứng gợn sóng động (gợn nước)] (https://blog.csdn.net/Kennethdroid/article/details/106556584)

- [Công cụ gỡ lỗi Android OpenGL ES] (https://blog.csdn.net/Kennethdroid/article/details/106695602)

- [Android OpenGL ES chuyển các mảng lớn sang các chương trình tạo bóng] (https://blog.csdn.net/Kennethdroid/article/details/109749018)

- [Đối tượng OpenGL ES thường được hỏi trong các cuộc phỏng vấn là gì? ] (https://blog.csdn.net/Kennethdroid/article/details/112379836)

- [Cái nào tốt hơn để hiển thị hình ảnh trong Android OpenGL ES] (https://blog.csdn.net/Kennethdroid/article/details/109339906)

- [Sử dụng OpenGL ES để tạo bộ lọc vẽ nhân vật cho trình phát video và máy ảnh] (https://blog.csdn.net/Kennethdroid/article/details/113379112)

- [Chuyển đổi định dạng hình ảnh từ RGB sang YUV bằng OpenGL] (https://t.1yb.co/uvfH)

- [Khi OpenGL ES chia sẻ bối cảnh, những tài nguyên nào có thể được chia sẻ? ] (https://t.1yb.co/uvfS)

- [Có bao nhiêu cách để kết xuất văn bản OpenGL ES? ] (http://mp.weixin.qq.com/s?__biz=MzIwNTIwMzAzNg==
