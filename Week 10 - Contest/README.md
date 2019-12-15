# Câu 1:
## Tạo class NhanVien:
- Thuộc tính: mã nhân viên, tên nhân viên, chức vụ, lương.	
- Phương thức:
  - Constructor (gồm mã, tên và chức vụ), Getter và Setter cho các thuộc tính
  - `HienThiThongTin()`: Hàm này sẽ hiển thị tất cả thuộc tính của NhanVien trên cùng 1 dòng
  - `TinhLuong()`:
    - Nếu chức vụ là "nhan vien" thì lương = 5000000;
    - Nếu chức vụ là "truong phong" thì lương = 8000000;
    - Nếu chức vụ là "giam doc" thì lương = 10000000;
    - Nếu chức vụ khác thì lương = 0;

:collision: Yêu cầu: Ở hàm main khởi tạo 4 nhân viên với các chức vụ là "nhan vien", "truong phong", "giam doc", "chu tich". TinhLuong() rồi HienThiThongTin() cho 4 người đó
# Câu 2:
## Tạo class ToTien:
- Thuộc tính: mã tờ tiền (có cả chữ và số), loại tiền(1k,2k,5k,10k)
- Phương thức:
  - Constructor (mã tờ tiền, loại tiền), Getter và Setter cho các thuộc tính
  - `HienThiThongTin()`: Hàm này sẽ hiển thị tất cả thuộc tính của ToTien trên cùng 1 dòng

:collision: Yêu cầu: Tạo mảng gồm 10 tờ tiền như dưới đây và thực hiện các chỉ mục (1) (2) (3)
```
ToTien ToThu1 = new ToTien("M110A634ABG","1k");
ToTien ToThu2 = new ToTien("M3255LINH45","1k");
ToTien ToThu3 = new ToTien("M3HIEU2AS34","1k");

ToTien ToThu4 = new ToTien("U13HTS34E","2k");
ToTien ToThu5 = new ToTien("982TUXP21","2k");
ToTien ToThu6 = new ToTien("38HIT7734","2k");

ToTien ToThu7 = new ToTien("65GSONGNGHIEN2","5k");
ToTien ToThu8 = new ToTien("G3C5WHZ3FDE324","5k");
ToTien ToThu9 = new ToTien("H34ITHUTS25551","5k");

ToTien ToThu10 = new ToTien("C7H10OTHAI13","10k");
```

(1) Anh Thụ giấu tên của những tờ có các tên của leader support trong những tờ tiền đó. HienThiThongTin() các tờ có chứa các từ sau `["SON","TU","THU","LINH","THAI","HIEU"]` 

(2) HienThiThongTin() các tờ có tổng các chữ số trong mã chia hết cho loại tiền. Ví dụ: `ToTien("HIT18082010","5k")` vì `1+8+0+8+2+0+1+0 % 5 <=> 20 % 5 == 0` hoặc `ToTien("HIT18082010","10k")` vì `1+8+0+8+2+0+1+0 % 5 <=> 20 % 10 == 0`

(3) Nhập k là số tiền cần đổi. HienThiThongTin() 3 tờ tiền có loại tiền cộng lại = k (1<=k<=20) đồng thời tổng mã các chữ số trong tờ tiền đó phải chia hết cho 2, các tờ phải khác nhau. Nếu không có in ra là Không có

  Input  | Output
------------- | -------------
.  | `Ma to tien: M3255LINH45, loai tien: 1k`
   `8`  |`Ma to tien: 982TUXP21, loai tien: 2k`
 .    |`Ma to tien: G3C5WHZ3FDE324, loai tien: 5k`
 
 # Câu 3
 - Đề bài: Tạo 2 class SoLienLac kế thừa TenLienLac để thực hiện bài toán sau:

TenLienLac  |
------------- |
=====Thuộc tính===== |
`pravate String ma`
`private String ten`
`private String soDienThoai`
=====Phương thức==== |
`void HienThiThongTin()`

SoLienLac  |
------------- |
============Thuộc tính=========== |
`private ArrayList <TenLienLac> SoLienLac`
============Phương thức========== |
`void ThemTenLienLac(TenLienLac A)`
`TenLienLac TimKiemID(String id)`
`void HienThiThongTinBangID(String id)`
`void SuaThongTinBangID(String id)`
`void XoaThongTinBangID(String id)`
`void HienThiToanBoThongTin()`

:collision: Yêu cầu: Tạo 5 TenLienLac bất kì sử dụng constructor. Tạo 1 sổ SoLienLac để lưu 5 TenLienLac này lại. Sử dụng thành công các phương thức có trong SoLienLac. 

:eyes: Chú thích thêm: 
- `ThemTenLienLac(TenLienLac A)`: cho phép thêm tên liên lạc.
- `TimKiemID(String id)`: sẽ trả về TenLienLac nếu tìm thấy.
- `HienThiThongTinBangID(String id)`: hiển thị thông tin của TenLiecLac có id như vậy.
- `SuaThongTinBangID(String id)`: tìm kiếm rồi sửa thông tin với yêu cầu cho phép sửa cái nào muốn sửa.
- `XoaThongTinBangID(String id)`: xóa TenLienLac đó.
 
## :gift: Bonus
- Top 5 bạn dành điểm cao nhất trong cuộc thi lần này sẽ được phần quà bí mật. (Nghe đâu đó hình như là vỗ tay .... Đùa đấy :v)
