# CatChuoi
Hàm cắt chuỗi từ một vị trí (STT) trong chuỗi cho đên khi gặp một ký tự, nếu không tìm thấy kết quả trả về là N/A. Tham số:
- str: chuỗi gốc, vd: "Diễn giải: Số: 123 Ngày: 10/10/2015"
- sttkytubatdaucat: vị trí (STT) bắt đầu cắt, vd: 10
- catdenkhigapkytunao: dừng cắt khi gặp ký tự được chỉ định dừng, vd: ":"
==> catchuoi("Diễn giải: Số: 123 Ngày: 10/10/2015", 11, ":"), kết quả: "Số:"
