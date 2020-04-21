# Tác giả
* Nguyễn Đức Thắng (leader) - Kỹ sư tài năng Toán Tin K61 - Đại học Bách Khoa Hà Nội
* Lương Thành Long - K60 Đại học Bách Khoa Hà Nội
* Phạm Xuân Nam Chính - Học viên cao học Khoa học dữ liệu 2019-B
# Giới thiệu
Cảm ơn những người cộng tác tìm hiểu cùng tôi. Đây là báo cáo về phương pháp tối ưu Adam trong Deep learning của chúng tôi. Được viết bằng Tiếng Việt.

Trong báo cáo, chúng tôi có trình bày chi tiết về các phương pháp tối ưu phổ biến hiện nay trong cộng đồng deep learning.
Từ những lý thuyết và tư tưởng căn bản nhất của gradient descent, chúng tôi giúp người đọc hiểu được ưu và nhược điểm của từng phương pháp, đi sâu vào bản chất toán học của chúng. 

Với gradient descent, phương pháp này là khởi nguồn cho mọi phương pháp sau này. Tuy có những nhược điểm, nhưng nó vẫn đang là phương pháp dễ hiểu và phổ biển nhất. Gradient khó vượt qua điểm cực tiểu và nó không tuỳ chỉnh learning rate cho từng tham số, có những tham số cần cập nhật timestep lớn sau mỗi bước, có những tham số lại chỉ cần timestep nhỏ sau mỗi bước. Vì vậy, 1 loạt các phương pháp tối ưu sau này ra đời nhằm khắc phục các nhược điểm của Gradient Descent như: momentum, NAG, AdaGrad, Adadelta, RMSProp và Adam. Riêng với phương pháp Adam, đây là phương pháp có thể nói là mạnh mẽ tại thời điểm hiện tại, chúng tôi đi sâu vào phương pháp này, bao gồm cả vấn đề hội tụ của phương pháp. Đây là một vấn đề khó và nặng bản chất toán học. Chúng tôi tham khảo từ nhiều nguồn để soạn thảo và chỉ ra những lỗi sai trong đánh giá sự hội tụ của phương pháp Adam. Và chúng tôi cũng giới thiệu về 3 phương pháp mở rộng từ thuật toán Adam là: Adamax, Nadam, AMSGrad. Riêng với AMSGrad, trong bài báo của các tác giả AMSGrad, các tác giả đã chứng minh Adam không hội tụ và đưa ra phương pháp này và cho rằng nó thực sự tốt hơn Adam. Tuy nhiên, các thực nghiệm gần đây cho thấy thực sự không hẳn như vậy. Vấn đề của Adam và AMSGrad vẫn là một vấn đề mở và đợi các nghiên cứu sau này.

Chúng tôi cũng thực nghiệm code lại các thí nghiệm và public code của các bài báo cho bạn đọc tham khảo. Các bạn có thể xem báo cáo ở file báo cáo pdf và xem code ở các file jupyter.

Hy vọng qua báo cáo này của chúng tôi, cộng đồng Deep learning Việt Nam có thể có cái nhìn sâu sắc hơn về bản chất các phương pháp tối ưu. Từ đó là nền tảng để tìm hiểu sâu hơn!

**Nguyễn Đức Thắng**

