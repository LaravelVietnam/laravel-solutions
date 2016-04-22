# laravel-solutions
A Q&amp;A board for helping members 

## Lý do có repo này?
Hầu hết thành viên đặt câu hỏi trên Facebook vì nó tiện. Tuy nhiên Facebook có những điểm bất lợi sau:
* Khó trả lời: giao diện commet của Facebook khiến viết giải thích và chia sẻ source code bất tiện.
* Người đi làm khó vào facebook hơn là github để có thể giúp đỡ bạn.
* Facebook dễ sao nhãng công việc. 
Tất nhiên để thay đổi thói quen không phải là chuyện dễ dàng, bạn có thể tạo câu hỏi ở đây và share link tới tất cả mọi nơi bạn muốn kể cả Facebook để có thể tìm kiếm sự giúp đỡ nhanh nhất từ cộng đồng.

## Bạn có thể hỏi gì ?
* Tất tần tật về PHP
* Tất tần tật về Laravel (hiện tại các framework khác chưa được hỗ trợ)
* Kinh nghiệm làm dự án, giải pháp công nghệ liên quan tới PHP và Laravel 
* Server Configuration

##Làm sao để bạn đặt một câu hỏi ?
* Đơn giản là tạo một Issues mới ở repo này bằng cách [Click vào đây](https://github.com/LaravelVietnam/laravel-solutions/issues/new)
* Đừng quên nhấn vào Star và Watch ở Repo để có thể nhận thông báo mới từ repo này

![](https://raw.githubusercontent.com/LaravelVietnam/laravel-solutions/master/star-and-watch-repo.png)

## Format của câu hỏi:

### Tiêu đề
Tiêu đề có định dạng: `[Mảng] Vấn đề`
Ví dụ:
- `[Hosting] Kết nối bằng SSH lên Godaddy bị lỗi abc`
- `[Package] Xử lý Header như thế nào?`

### Nội dung
Nên theo các quy ước sau bạn sẽ được hỗ trợ nhanh hơn:
- Nếu là lỗi, cần **copy** thông báo lỗi chính, và đoạn [Stack trace](https://en.wikipedia.org/wiki/Stack_trace) (nếu có);
- Copy thêm dòng code hoặc đoạn code đang chạy mà bị báo lỗi;
- Code nên đánh dấu theo [Markdown Syntax](https://guides.github.com/features/mastering-markdown/, "Github Mastering Markdown") để dễ đọc, cụ thể là dùng dấu \` bao inline code: \`code\` => `code`
- Với đoạn code thì dùng 3 dấu \`, ví dụ

\`\`\`php

<?php

echo "Hello Laravel Vietnam";

?>

\`\`\`

sẽ cho ra

```php
<?php
echo "Hello Laravel Vietnam";
?>
```
- Code indent (thụt dòng) vào bằng 4 khoảng trắng (4 space)
- Trong trường hợp bạn gặp lỗi cần debug, song song với việc chụp màn hình, hãy copy cả những đoạn lỗi vào nội dung câu hỏi để những bạn khác nếu gặp lỗi này có thể dùng Google search hay Gihub search để tìm ra, tránh việc đặt câu hỏi thừa không cần thiết.


