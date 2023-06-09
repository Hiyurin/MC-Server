
# Giới thiệu về phần mềm Folia
[](https://raw.githubusercontent.com/PaperMC/Folia/master/folia.png)

## Về Dự án Folia

Folia là dự án mới nhất của PaperMC, được tạo ra nhằm mục đích giúp cho các máy chủ Minecraft chạy đa luồng và khu vực hóa máy chủ. Mục tiêu của dự án này là cung cấp khả năng mở rộng và hiệu suất tốt hơn, đồng thời khắc phục một số sự cố tồn tại từ lâu vốn là yếu tố hạn chế để mở rộng quy mô máy chủ Minecraft.

### Đặc điểm của máy chủ

- **Khu vực (Chunk):** Các chunk được tạo một cách độc lập. Mỗi khu vực độc lập có vùng đánh dấu riêng, được đánh dấu ở tốc độ thông thường (20TPS). Các vùng đánh dấu được thực thi song song trên một nhóm luồng. Không còn luồng chính nữa, vì mỗi vùng có "luồng chính" riêng thực hiện toàn bộ vùng đánh dấu. Đối với một máy chủ có nhiều người chơi, Folia sẽ tạo nhiều khu vực và đánh dấu tất cả vùng song song - điều này sẽ hoạt động tốt hơn đáng kể so với phương pháp đánh dấu lần lượt từng thế giới hiện tại.
- **Lợi ích của Folia:** Khi máy chủ có các vùng không sử dụng và mỗi khu vực hiện được đánh dấu độc lập nên máy chủ sẽ tốn ít tài nguyên hơn khi xử lí. Điều này sẽ dẫn đến hiệu suất tăng đáng kể, đặc biệt là với phần cứng mạnh mẽ. Các chế độ trò chơi như sinh tồn và skyblock người chơi thường tách biệt nhau, hoàn toàn có thể sử dụng bộ tạo vùng và cung cấp các mức tăng hiệu suất bổ sung.
- **Giảm chi phí thuê máy chủ:** Chủ sở hữu máy chủ hiện có nhiều tùy chọn hơn khi chọn CPU phù hợp cho máy chủ Minecraft của họ. Hiệu suất đơn luồng không còn là yếu tố duy nhất liên quan trực tiếp đến hiệu suất. Thay vào đó, mô hình CPU có tốc độ xung nhịp thấp hơn một chút nhưng số lượng lõi cao hơn có thể không chỉ tiết kiệm cho chủ sở hữu máy chủ một vài đô la mà còn mang lại nhiều lợi ích hơn so với các CPU hàng đầu, thường có chi phí cao.

## Kết luận

Folia là một dự án đầy tham vọng nhằm đưa máy chủ Minecraft lên một tầm cao mới "đa luồng và khu vực hóa". Tôi hy vọng bài đăng này cung cấp cho bạn thêm một chút thông tin về dự án. 
