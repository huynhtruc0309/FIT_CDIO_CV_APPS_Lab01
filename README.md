# FIT_CDIO_CV_APPS_Lab01
## Giới thiệu
Chúng ta đã quá quen với việc sử dụng MNIST. MNIST là cơ sở dữ liệu về chữ số viết tay, được sử dụng rất rộng rãi trong cồng đồng AI/ML. MNIST thường được thử đầu tiên khi có một thuật toán phân loại ảnh mới. Một số người nói “If it doesn’t work on MNIST, it won’t work at all”. Nhưng đồng thời, “Well, if it does work on MNIST, it may still fail on others.”

Fashion-MNIST được tạo ra gần đây với kích thước tương tự như MNIST nhưng các ảnh là các ảnh xám của trang phục với các nhãn: (0) T-shirt/top, (1) Trouser, (2) Pullover, (3) Dress, (4) Coat, (5) Sandal, (6) Shirt, (7) Sneaker, (8) Bag, (9) Ankle boot. Fashion-MNIST cũng có 10 class, 60000 ảnh cho training, 10000 ảnh cho test, mỗi ảnh có kích thước 28x28 pixel và là các ảnh xám với chỉ một channel. Dưới đây là một ví dụ về ảnh của class (2) Pullover.

Tác giả của Fashion-MNIST cho rằng cần phải thay thế MNIST vì:
+ MNIST đã trở nên quá dễ. Rất nhiều thuật toán deep learning đã đạt được độ chính xác lên tới 99.7%, ngay cả KNN cũng đạt được trên 96%. Rất khó để đánh bại con số 99.7%, và nếu mô hình của bạn đạt được con số này, ta vẫn khó có thể kết luận ngay đó là một mô hình tốt.
+ MNIST được sử dụng quá nhiều đến mức nhàm chán.
+ MNIST không đại diện cho các bài toán computer vision hiện đại.

## Quá trình xây dựng giải pháp
Notebook thực hiện theo các bước:

+ Bước 1: Chuẩn bị dữ liệu

+ Bước 2: Xây dựng kiến trúc mô hình

2.1) Mô hình Baseline: Multi Layer Perceptron

2.2) Mô hình cải tiến: Convolutional Neural Network

+ Bước 3: Đánh gía kết quả mô hình trên tập test

## Báo cáo kết quả
+ Mô hình Baseline: Multi Layer Perceptron
Testing_error : 13.122900888988166
Accuracy_test : 0.8586783439490446

+ Mô hình cải tiến: Convolutional Neural Network
Testing_error : 0.185975147565459
Accuracy_test : 0.9328224522292994
