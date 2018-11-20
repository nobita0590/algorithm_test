## Nội dung yêu cầu bài test giải thuật

Viết một function có 2 biến truyền vào đều là kiểu string. Giá trị trả về là một Array bao gồm các biến kiểu int

```
function strIndex(str string,substr string) []int {
    // Code here
}
```

### Test case

```
var str = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem vel erat leo."
strIndex(str,"Lorem") = [0,57]
strIndex(str,"Loremipsum") = []
strIndex(str,"it ame") = [19]
```

### Lưu ý: 
+ Ứng viên không được sử dụng các hàm index built in để thực hiện tác vụ này. 
+ Ứng viên có thể chọn một trong các ngôn ngữ mà mình biết để hoàn thành.
+ Bài kiểm tra cần có giao diện người dùng và có thể hiển thị tương tác trên màn hình, và tài liệu hướng dẫn cài đặt.
+ Ứng viên gửi bài kiểm tra bằng cách tạo 1 pull request đến repository này hoặc gửi file nén đến địa chỉ email skynet0590@gmail.com
+ Tiêu đề vui lòng ghi rõ: Ho_Ten_SDT_lien_he