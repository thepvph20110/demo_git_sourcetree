# Quản lý dự án với Github và Source tree

## Giới thiệu

- Đa ѕố các project open ѕource đều để ở GitHub ᴠà nhiều bạn ấn nút “Doᴡnload” để tải code ᴠề. Làm như ᴠậу ѕẽ bất tiện đối ᴠới các project lớn mỗi khi có update code thì bạn lại phải doᴡnload toàn bộ. Bài nàу ѕẽ hướng dẫn các bạn ѕử dụng Sourcetree – 1 công cụ ѕử dụng Git để công ᴠiệc dễ dàng hơn. Với giao diện GUI thân thiện các bạn có thể dễ dàng хem log của code. Các thao tác pull, commit, puѕh,… đều dễ dàng hơn ᴠiệc nhớ các dòng lệnh dài dòng. Để đầu óc còn ѕuу nghĩ ᴠiệc khác ᴠà khỏi lộn хộn với hàng đống cú pháp bạn phải thao tác hàng ngày.

## Git là gì?

- Để làm việc với **Git** bạn phải hiểu **Git** là gì? và dùng để làm gì ?
- Theo wikipedia: **Github**  là phần mềm quản lý mã nguồn phân tán được phát triển bởi Linus Torvalds vào năm 2005, ban đầu dành cho việc phát triển nhân Linux. Hiện   nay, Git trở thành một trong các phần mềm quản lý mã nguồn phổ biến nhất. Git là phần mềm mã nguồn mở được phân phối theo giấy phép công cộng GPL2.
- Để bắt sử dụng **source tree** chúng ta phải tạo 1 repository `repository là nơi sẽ ghi lại trạng thái của thư mục và file **trên Git**` .
  Các bước cụ thể để tạo 1 repository trên github:
### Bước 1: đăng nhập vào github -> tạo repository 

  ![Screenshot 2022-08-16 174124](https://user-images.githubusercontent.com/109200115/185024111-5dea9ad3-c1f5-47c8-8c77-f5e05d5eb715.png)

### Bước 2: nhập tên -> tích vào README.md -> click vào button (Create repository)

  ![image](https://user-images.githubusercontent.com/109200115/185024388-fe940a0c-affd-42f5-bbd1-4b24be3e15be.png)

### Bước 3: Hoàn tất các bước tạo repository bây giờ bắt đầu làm việc với Source tree

  ![image](https://user-images.githubusercontent.com/109200115/185024547-d5560a4b-397a-48a2-b5ba-15795e93a6d3.png)


## Source tree là gì ?
- Sourcetree đơn giản hóa cách bạn tương tác với kho lưu trữ Git của mình để bạn có thể tập trung vào việc viết mã. Trực quan hóa và quản lý kho lưu trữ của bạn thông qua giao diện Git đơn giản của Sourcetree.
- [Link Download source tree](https://www.sourcetreeapp.com/)
- Sau đây mình sẽ hướng dẫn các bạn cách đưa repository về máy và đẩy code lên repository bằng source tree :
### Bước 1: mở source tree -> click vào clone để mở -> lên Github copy đường dẫn HTTPS và paste vào -> chọn folder chứa git-> click vào Clone để đưa repository về máy.

  ![image](https://user-images.githubusercontent.com/109200115/185025416-0ad3013c-a404-4e08-99dc-05a7da8ea1a8.png)
  
  ![image](https://user-images.githubusercontent.com/109200115/185025471-a6314e11-c806-4a06-b880-fecdf777a105.png)

### Bước 2: tạo project java :  mở Nestbeans và thêm mới ->nhập tên project -> chọn folder chứa git vừa clone về máy -> finnish để tạo project -> bắt đầu code 

  ![image](https://user-images.githubusercontent.com/109200115/185025530-75c970d1-8465-43b3-aab8-e4d81a7815a2.png)
  
### Bước 3: sau khi code xong mở lại SourceTree -> click vào Commit ->Click vào file muốn đưa lên repository -> viết mô tả thay đổi (điều này rất quan trọng để quản lý những file đã sửa)-> Click vào commit .

  ![image](https://user-images.githubusercontent.com/109200115/185025648-f18f2a57-e28a-4ae3-a3d9-4ed60140b933.png)
  
  ![image](https://user-images.githubusercontent.com/109200115/185025680-a71706b2-bfad-4e1c-bda3-4e5bff83e1c5.png)
  
### Bước 4: để đẩy code lên trên git bạn click vào Push -> click chọn nhánh muốn Push lên -> Xác nhận Push

  ![image](https://user-images.githubusercontent.com/109200115/185025772-ba47938b-1fa9-459e-8743-9a2262ffe42a.png)
  
  ![image](https://user-images.githubusercontent.com/109200115/185025795-330062fc-9d42-4316-ae27-62b32d662724.png)
  
### Bước 5: kiểm tra lại repository 

  ![image](https://user-images.githubusercontent.com/109200115/185025858-a084d543-d60b-4e12-84cf-6dc700802d74.png)



