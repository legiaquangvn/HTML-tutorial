## Cấu trúc của một trang web HTML

- [bấm vào đây để đến đường dẫn của bài học](https://codesandbox.io/s/github/legiaquangvn/HTML-tutorial/tree/master/2-A-Webpage-Structure?file=/sample-web-page.html) 
  - trong phần browser, copy and paste link `https://32tez.csb.app/sample-web-page.html` để xem trang web

- Một trang web có tận cùng là đuôi `.html`, bạn cũng có thể gọi đó là một trang HTML vì nó sử dụng ngôn ngữ HTML để môt tả nội dung.
- Bạn cứ hình dung một trang HTML là một trang văn bản. Cấu trúc của nó bao gồm
  - Tiêu đề: dùng để mô tả tiêu đề và các ứng dụng mà văn bản của bạn có thể dùng (bạn có thể bỏ qua cho đỡ phức tạp, sau này mình sẽ đề cập sau)
  - Phần nội dung: dùng để trình bày văn bản.
    - các nội dung trong văn bản được thể hiện dưới dạng các thẻ (gọi là tag)
    - các thẻ khác nhau sẽ có những thuộc tính và để thể hiện các mục đích khác nhau, thí dụ:
      - thẻ `<h1>`: thể hiện tiêu đề lớn
      - thẻ `<p>`: thể hiện một đoạn văn bản
      - thẻ `<link>`: thể hiện một đường nối đến một văn bản khác, một trang web khác
      - thẻ `<img>`: để hiển thị một bức ảnh.
  - Trang văn bản sẽ nằm giữa thẻ `<html> ... </html>`
    - `html` là tên thẻ.
    - `<html>` thể hiện đây là điểm bắt đầu của một thẻ (hay là mở thẻ)
    - `</html>` thể hiện đây là điểm kết thúc của một thẻ (hay là đóng thẻ)
    - `/` là ký hiệu kết thúc của một thẻ.
  - Một thẻ bao giờ cũng đi theo một đôi: mở đầu và kết thúc `<tên-thẻ>nội dung của thẻ</tên-thẻ>`.
  - Phần đầu không hiển thị nằm giữa thẻ `<head> ... </head>`. Phần này để cho các mục đích khai báo CSS (tô màu, trang trí cho các thẻ), javascript (tạo các hiệu ứng động) mà chúng ta sẽ học ở phần khác sau.
  - Phần thân văn bản nằm giữa thẻ `<body> ... </body>`
  - Thí dụ:
    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <title>Page Title</title>
        </head>
        <body>
            <h1>This is a Heading</h1>
            <p>This is a paragraph.</p>
            <img src="./HTML-document-structure.svg" width="400" height="400" />
        </body>
    </html>
    ```
      - `<!DOCTYPE html>` là để chỉ ra rằng đây là một văn bản html, nó là mặc định mà các trang html đều có. Giờ nó không quan trọng trong việc học của chúng ta.
  


