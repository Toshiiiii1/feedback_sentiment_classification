# Feedback Sentiment Classification Project

## Mục tiêu dự án

Dự án này nhằm mục đích phát triển một hệ thống tự động để phân loại feedback của khách hàng thành hai loại chính: tích cực và tiêu cực. Điều này giúp các doanh nghiệp hiểu rõ hơn về trải nghiệm và ý kiến của khách hàng về sản phẩm hoặc dịch vụ của họ.

## Công nghệ và Công cụ

- **Ngôn ngữ lập trình:** Python 3.8+
- **Thư viện chính:**
  - scikit-learn: Để xây dựng mô hình machine learning.
  - pandas: Để xử lý dữ liệu.
  - numpy: Để thực hiện các phép tính toán học.
  - nltk hoặc spaCy: Để xử lý ngôn ngữ tự nhiên (NLP).
- **Framework:** Flask hoặc Django (nếu dự án cần một API hoặc giao diện web để tương tác).

## Tập dữ liệu

Tập dữ liệu bao gồm feedback từ khách hàng đã được thu thập từ nhiều nguồn khác nhau như email, trang web, và các kênh mạng xã hội. Mỗi mẫu dữ liệu sẽ bao gồm văn bản feedback và nhãn (tích cực/tiêu cực).

## Cách thức hoạt động

1. **Tiền xử lý dữ liệu:** Làm sạch dữ liệu và chuyển đổi văn bản thành dạng có thể xử lý được bởi mô hình machine learning.
2. **Huấn luyện mô hình:** Sử dụng dữ liệu đã được tiền xử lý để huấn luyện mô hình phân loại sentiment.
3. **Đánh giá mô hình:** Sử dụng các phép đo như độ chính xác, F1-score để đánh giá hiệu suất của mô hình.
4. **Triển khai mô hình:** Tích hợp mô hình vào một ứng dụng web hoặc API để phân loại feedback thực tế từ khách hàng.

## Cài đặt

Mô tả cách thiết lập môi trường và chạy dự án:

```bash
git clone https://github.com/Toshiiiii1/feedback_sentiment_classification.git
cd yourproject
pip install -r requirements.txt
