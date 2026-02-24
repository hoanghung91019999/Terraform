# Terraform - Infrastructure as Code 
- Từ cái tên của Infrastructure as Code thì ta có thể hiểu đơn giản là ta sẽ viết code để mô tả và cung cấp (provisioning) infrastructure của chúng ta 😁. Từ Infrastructure tiếng việt có nghĩa là hạ tầng, còn ở trong ngành IT của chúng ta thì mình hiểu nó là hạ tầng của hệ thống, bao gồm máy chủ, mạng, gateway, database, tất cả những thứ cần thiết để triển khai ứng dụng của chúng ta trên môi trường server. Infrastructure as Code thì chắc có lẽ được sử dụng phổ biến nhất trên môi trường Cloud.
- Terraform là một open-source của HashiCorp, chuyên dùng để provisioning infrastructure, ta chỉ việc viết code, rồi gõ một vài câu CLI đơn giản, nó sẽ tạo ra Infrastructure cho ta, thay vì ta với lên web console bấm bấm rất tốn thời gian.
-  workflow

- <img width="683" height="326" alt="image" src="https://github.com/user-attachments/assets/7bae24aa-714c-450b-9df1-e85baa99e78f" />
- <img width="699" height="385" alt="image" src="https://github.com/user-attachments/assets/3932f004-b4db-4c5f-b3be-3a0eec0af630" />
- Tại sao nên dùng Terraform :
  + Dễ xài.
  + Open source và miễn phí.
  + Declarative programing: chỉ diễn tả những thứ bạn cần và Terraform làm cho bạn.
  + Có thể cung cấp hạ tầng cho nhiều cloud khác nhau như AWS, GCP, Azure trong cùng một file cấu hình, này ta gọi là Cloud-agnostic.

- So sánh với các tool khác:
  + Terraform: declarative (bạn nói “muốn gì”, Terraform làm “thực hiện”)
  + Ansible: procedural / configuration management (bạn nói “làm gì theo bước”)

- Khái niệm cơ bản
  + Provider : Nhà cung cấp hạ tầng (AWS, Azure, vSphere…)
  + Resource : Một đối tượng hạ tầng (EC2, S3, VPC…)
  + Module : Gói hạ tầng tái sử dụng
  + variable : Biến input để tùy chỉnh hạ tầng
  + Output : Thông tin xuất ra sau khi apply (IP, URL…)
  + State : File .tfstate lưu trữ trạng thái thực tế của hạ tầng
 
- <img width="734" height="339" alt="image" src="https://github.com/user-attachments/assets/b91e4a20-9041-4db2-a6de-6e8a03d5e847" />
- link tham khảo : https://viblo.asia/p/terraform-series-bai-1-infrastructure-as-code-va-terraform-maGK7Bqa5j2


 
