
# Hướng dẫn một số lệnh Github cơ bản

### Giới thiệu

- Bài viết sẽ hướng dẫn tạo một repository và một số lệnh cơ bản
- Các bạn có thể áp dụng để tải thư mực lên và lưu trữ một số  dữ liệu quan trọng
- Bài viết sau mình sẽ hướng dẫn các bạn thực hiện trong một project

### Tạo repository

- Trước tiên, bạn cần tạo một tài khoản github trước
- Ở đây mình sử dụng tài khoản của mình. Dưới đây là những repository đã được tạo từ trước.

![image_repository]()

- Bạn chọn **New** và điền đầy đủ thông tin để tạo một repository

![image_new_respository]()

- Ở đây mình đã tạo ra thành công một repository mới với tên là **Learning_Gituhb**

![image_complete_new_respo]()

- Như vậy bạn đã tạo thành công một repository mới. Tiếp theo sẽ là vài lệnh cơ bản trong Github

### Các lệnh cơ bản

- Sao chép (Clone) một repository về với lệnh:


```python
git clone /Đường dẫn để clone repository đấy/
```

    - Ở đây ta sẽ lấy đường dẫn clone này về và chạy với lênh terminal 

![image_clone]()

    - Ví dụ:


```python
git clone https://github.com/dtrungphong/Learning_Github.git  
```

    - Ngoài ra bạn có thể sử dụng một số cách khác như Download dưới dạng file Zip về và giải nén
    - Sau khi chúng ta clone về sẽ có thư mục chứa tên của repository

- Thao tác tải thư mục lên github với repository đã được clone về từ trước:


```python
git add *
```

    - Với git add * sẽ giúp bạn cập nhật toàn bộ thay đổi trong thư mục được repository về
    - Ngoài ra bạn có thể dùng git add 'tên folder cần cập nhật lên'
    - Ở đây nó đang nằm chờ ở vùng chỉ mục và chờ được cập nhật lên trên github


```python
git commit -m "Nội dung"
```

    - Nó sẽ giúp bạn ghi chú phần cập nhật thay đổi và tải lên Head trước khi được cập nhật lên github


```python
git push origin master
```

    - Nó giúp giúp bạn đẩy (push) những thay đổi lên trên trang github
    - Lưu ý phần này đôi khi nó sẽ yêu cầu bạn cần nhập tài khoản mật khẩu github để xác định bạn là ai

- Lệnh Kiểm tra bạn đang ở nhánh (Branch) nào:


```python
git status
```

- Liệt kê những danh sách đang được sử dụng 


```python
git config --list
```

- Xem thông tin hỗ trợ cho một câu lệnh của Github:


```python
git help clone
```

- Ngoài ra còn nhiều lệnh khác nữa mình sẽ xây dựng và đóng góp bổ sung trong phần 2 đối với một dự án project
- Mong được sự đóp góp và góp ý của các bạn về bài viết

**Contact:**
- Phone: +84352083974
- Mail: dtphong010199@gmail.com

### Nguồn hỗ trợ

- Hỗ trợ từ [github](https://help.github.com/en)
- [Git Book](https://book.git-scm.com/)
- Link tiếng Việt 1 [tham khảo](https://rogerdudler.github.io/git-guide/index.vi.html)
- Link tiếng Việt 2 [tham khảo](https://viblo.asia/p/tap-hop-nhung-cau-lenh-git-huu-dung-dWrvwWr2vw38)
