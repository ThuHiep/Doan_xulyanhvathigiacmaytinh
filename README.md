
# Ứng dụng AlexNet trong phân loại tế bào máu từ ảnh hiển vi
<img width="1124" height="472" alt="image" src="https://github.com/user-attachments/assets/137c1043-4d51-4a03-884d-39058696b485" />


## Tác giả:
Họ và Tên: Đinh Thị Thu Hiệp

MSHV: 250101085
## Giới thiệu

Phân loại tế bào máu là một bước quan trọng trong chẩn đoán các bệnh lý huyết học. Tuy nhiên việc phân tích thủ công dưới kính hiển vi đòi hỏi nhiều thời gian và phụ thuộc vào kinh nghiệm của chuyên gia.

Dự án này áp dụng Deep Learning với kiến trúc AlexNet Convolutional Neural Network (CNN) để tự động phân loại các loại tế bào máu ngoại vi bình thường từ ảnh kính hiển vi.

Mục tiêu của dự án là xây dựng một mô hình có khả năng hỗ trợ tự động hóa quá trình phân tích tế bào máu, góp phần hỗ trợ các hệ thống chẩn đoán y học thông minh.
## Bộ dữ liệu

Bộ dữ liệu sử dụng gồm 17,092 ảnh tế bào máu ngoại vi bình thường, được thu thập bằng hệ thống CellaVision DM96 tại Hospital Clinic of Barcelona.

### Các loại tế bào

1. Neutrophils (Bạch cầu trung tính)
2. Eosinophils (Bạch cầu ái toan)
3. Basophils (Bạch cầu ái kiềm)
4. Lymphocytes (Tế bào lympho)
5. Monocytes (Tế bào đơn nhân)
6. Immature granulocytes (Bạch cầu hạt chưa trưởng thành)
7. Erythroblasts (Nguyên hồng cầu)
8. Platelets (Tiểu cầu)
