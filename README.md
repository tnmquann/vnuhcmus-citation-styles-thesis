# Mẫu trích dẫn cho khóa luận tốt nghiệp Đại học Khoa học Tự nhiên - ĐHQG TP.HCM

> **Nguồn tham khảo chính: [ Hướng dẫn sử dụng Zotero - FSH Education Channel](https://fsh.org.vn/vietnamese-utf-8/huong-dan-su-dung-zotero---fsh-education-channel-c123a180.html)**

* Mẫu trích dẫn mới của Bộ Giáo Dục và Đào Tạo có thể tải tại đây:
	* [Tiếng Việt](https://www.zotero.org/styles/vietnam-ministry-of-education-and-training-vi)
	* [Tiếng Anh](https://www.zotero.org/styles/vietnam-ministry-of-education-and-training-en)

## Hướng dẫn nhập trích dẫn cho Zotero
* Vào folder **Zotero** và tải file `*.csl` phù hợp với khóa luận.
* Ở giao diện chính của Zotero, chọn Edit > Preferences.
* Tại mục Cite chọn vào icon `+` ngay dưới danh sách mẫu trích dẫn hiện có.
* Chọn vào file `*.csl` vừa tải và chọn OK.
* Nhấn OK để lưu lại mẫu.

## Lưu ý
- Để xếp theo ngôn ngữ thì các bạn chú ý trong Zotero có phần Language cho mỗi tài liệu tham khảo. Mặc định tiếng anh sẽ là "en" hoặc "English" (bản Zotero 5+). Các tài liệu tiếng Việt thì các bạn đánh là "vi" hoặc "Vietnamese" (Bản Zotero 5+). Như vậy style sẽ xếp theo đúng thứ tự là tài liệu tiếng Việt lên trên tài liệu tiếng Anh.
- Thêm chữ "Tiếng Việt" và "Tiếng Anh" để giống mẫu cũ của Bộ Giáo Dục và Đào Tạo.
- **Style này do phải sử dụng một số marco không phù hợp với yêu cầu hiện tại của Zotero nên không thể đưa lên server chung của Zotero như 2 style ở trên.**

## Một số lỗi thường gặp
### Trích dẫn không sắp xếp theo alphabet.
> *Xem thêm tại [đây](https://tex.stackexchange.com/questions/477949/biblatex-with-biber-splits-long-name-to-first-and-last-name)*
* Một số tạp chí có quy định vị trí đặt họ/tên tác giả khác nhau, hoặc họ/tên tác giả được đặt khác (VD: Ở Việt Nam thì "Họ" được đặt ở trên cùng, khác với các nước phương Tây là đặt "Họ" ở cuối. Ngoài ra, trích dẫn này dựa vào hướng dẫn mẫu của [ACM SIGCHI Proceedings](https://citationsy.com/styles/acm-sigchi-proceedings), do đó hầu hết metadata sẽ được tách theo label `last_name` của `Author`, nếu `last_name` có nhiều hơn 1 từ thì Zotero sẽ sắp xếp lại dựa vào từ cuối cùng trong `last_name`.

<p align="center">
  <img src="https://github.com/tnmquann/vnuhcmus-citation-styles-thesis/assets/56569936/05f9752f-2916-4f6a-b897-f6b2cbc4ed6a" />
</p>
<p align="center">
<i> Mô tả vị trí trong mục "Author" của Zotero </i>
</p>

* Lúc này bạn chỉ cần vào lại metadata của trích dẫn và chỉnh lại phần `Author` sao cho phù hợp với yêu cầu trích dẫn và tải lại Zotero là được. (Lưu ý: Nếu chỉnh lại có thể sẽ ảnh hưởng đến thứ tự ban đầu của Họ - Tên tác giả, cần cân nhắc trước khi tiến hành).
