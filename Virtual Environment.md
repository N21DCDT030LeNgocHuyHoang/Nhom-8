# Cài đặt môi trường ảo cho đồ án phân loại
# phiên bản và thư viện được sử dụng trong bài
# Công Cụ Lập Trình và Thư Viện 
# Ngôn Ngữ Lập Trình và IDE:
# ●	Ngôn ngữ: Python.
# ●	Môi trường phát triển tích hợp (IDE): Colab, Jupyter Notebooks, Visual Studio Code.
# Thư Viện:Pandas, numpy, Matplotlib, seaborn, category_encoders, scikit_learn, pasty, hyperopt, xgboost, 
# Môi trường lập trình – python 3.12.6
# Thư viện	Phiên bản
# numpy 	1.24.4
# pandas	1.3.0
# seaborn 	0.13.2
# category_encoders	2.2.2
# scikit_learn	0.24.2
# patsy 	0.5.6
# os 	
# hyperopt 	0.2.7
# xgb	1.7.5
# matplotlib.pyplot	
# Công Cụ Trực Quan Hóa:
# ●	Matplotlib: Như đã đề cập, dùng để vẽ biểu đồ và trực quan hóa dữ liệu.
# ●	Seaborn: Thư viện xây dựng trên Matplotlib, cung cấp các giao diện cao cấp và các biểu đồ đẹp hơn để trực quan hóa dữ liệu.
# Hướng dẫn cài đặt môi trường ảo
1. Mở Anaconda Prompt:
Bạn cần sử dụng Anaconda Prompt hoặc Terminal (nếu đang sử dụng MacOS/Linux) để thực hiện các lệnh.
2. Tạo một môi trường ảo mới:
Để tạo môi trường ảo mới, sử dụng lệnh sau trong Anaconda Prompt:

conda create --name myenv
myenv là tên của môi trường bạn muốn tạo (bạn có thể thay bằng tên khác).
Nếu bạn muốn tạo môi trường với một phiên bản Python cụ thể, bạn có thể thêm python=3.x vào lệnh, ví dụ:

conda create --name myenv python=3.8
3. Kích hoạt môi trường ảo:
Sau khi tạo xong, để sử dụng môi trường ảo, bạn cần kích hoạt nó bằng lệnh:

conda activate myenv
Khi môi trường được kích hoạt thành công, tên môi trường sẽ xuất hiện ở bên trái của dòng lệnh, cho thấy rằng bạn đang ở trong môi trường đó.

4. Cài đặt các gói/thư viện:
Khi môi trường đã được kích hoạt, bạn có thể cài đặt các thư viện hoặc gói cần thiết. Ví dụ:

conda install numpy
Hoặc, nếu thư viện không có trong Anaconda repository, bạn có thể dùng pip:

pip install package_name
5. Danh sách các môi trường hiện có:
Để liệt kê tất cả các môi trường ảo bạn đã tạo, bạn có thể dùng lệnh:

conda info --envs
6. Hủy kích hoạt môi trường ảo:
Khi hoàn thành công việc và muốn thoát khỏi môi trường ảo, bạn sử dụng lệnh:

conda deactivate
7. Xóa môi trường ảo:
Nếu bạn không còn cần sử dụng một môi trường ảo và muốn xóa nó, sử dụng lệnh sau:

conda remove --name myenv --all
Lệnh này sẽ xóa môi trường myenv cùng với tất cả các gói thư viện liên quan.

Tóm tắt các lệnh chính của Anaconda:
Tạo môi trường ảo:
conda create --name myenv
Kích hoạt môi trường ảo:
conda activate myenv
Cài đặt thư viện:
conda install library_name
Hủy kích hoạt môi trường ảo:
conda deactivate
Xóa môi trường ảo:
conda remove --name myenv --all
Việc sử dụng Anaconda để quản lý môi trường lập trình và cài đặt các thư viện là một cách thuận tiện và mạnh mẽ, giúp bạn tránh xung đột giữa các phiên bản thư viện trong các dự án khác nhau.
