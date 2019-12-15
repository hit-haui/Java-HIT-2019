<<<<<<< HEAD
:speech_balloon: Bài tập về nhà có lẽ đã trở thành món ăn tinh thần của các bạn rồi. Chúng ta gần như đã đi được hơn một nửa chặng đường của lớp học. Phần bài tập của các bạn làm từ trước tới giờ đã chiếm tầm 80% kiến thức rồi đó. Hãy cố gắng đi đến vạch đích nào.
# Bài 1 (Easy):
Tạo 5 constructor của class ConHeo với:
- thuộc tính: tên, cân nặng, tuổi
- phương thức: Hiển thị thông tin 
=> Tạo và hiển thị 5 đối tượng tạo bằng 5 constructor khác nhau
# Bài 2 (Easy):
Tạo class MayTinh với:
- thuộc tính: không có
- phương thức: TinhTong(float a,float b); TinhTong(float a,float b,float c); TinhTong(float a[]);
=> Ở hàm main tạo một MayTinh, tạo giá trị và sử dụng hàm tính tống. Các hàm đều là kiểu trả về và hiển thị hàm TinhTong đó.
# Bài 3 (Normal):
Tạo class CauLacBo gồm:
- thuộc tính:
  - private Leader A;
  - private Support B;
  - private Member C:
- phương thức: Hiển thị thông tin

Leader được định nghĩa như sau:
- thuộc tính: tên, tuổi, số ngày lãnh đạo.
- phương thức: Hiển thị thông tin

Support được định nghĩa như sau:
- thuộc tính: tên, tuổi, tên các thành viên trong nhóm.
- phương thức: Hiển thị thông tin

Member được định nghĩa như sau:
- thuộc tính: tên, ngày hoạt động, số ngày nghỉ trong lớp.
- phương thức: Hiển thị thông tin

=> Dùng constructor tạo một CauLacBo và hiển thị thông tin

# Bài 4 (Very Super Ultra Mega Ultimate Extreme):
Làm theo hướng thuần hướng đối tượng:
- [XEM ĐỀ BÀI](Extreme.md)

## :warning: `Lưu ý:`
- Có 2 cách sắp đặt class như dưới đây.

Newbie
![image](https://user-images.githubusercontent.com/52252046/67147697-34cd7200-f2c1-11e9-94ee-12dcd0d0bb17.png)
Professional
![image](https://user-images.githubusercontent.com/52252046/67147726-8ece3780-f2c1-11e9-86a2-12754b2900ee.png)
- Lựa chon:
  - Làm bài 1,2,3
  - Làm bài 4
## :gift: Bonus
- Hoàn thành bài 4 và đúng hơn 70% sẽ được cộng 2 điểm cho bài kiểm tra cuối cùng.
=======
:speech_balloon: Bài tập tuần nãy sẽ tổng hợp kiến thức Java, từ dễ đến khó, phân theo dạng chủ đề.
# Bài 1 (Dễ, chủ đề: hàm):
- Đề bài: tạo các hàm sau và gọi `HienThiHam(a,b,c)` ở hàm `Main` với a,b,c tùy ý. 
```
  int TinhTong(int a,int b,int c) // Tổng 3 số a+b+c
  int TinhTheoCongThuc(int a,int b,int c) // Công thức: ((a / b)-c)/2
  int ChuyenThanhString(int a,int b,int c) // abc -> "abc". VD: a=1,b=2,c=3 -> đáp án: "123"
  
  void HienThiHam(int a,int b,int c) //Trong này sẽ hiển thị mọi kết quả các hàm trên
```
# Bài 2 (Dễ, chủ đề: nhánh):
- Đề bài: Anh Tú hay xem phim SIÊU NHÂN HEO vào mỗi tối nên tiền điện của anh tăng khá cao.
- Yêu cầu: Nhập `n` là số số điện anh Tú dùng để xem phim. Hiển thị ra số tiền mà anh Tú dùng để xem phim HEO.
  - Với 50 số đầu: 4000/số
  - Với 50 số sau: 3000/số
  - Với các số còn lại nữa thì tiền điện sẽ được giảm 10 đồng mỗi một số còn lại.

Input  | Output
------------- | -------------
`101`  | `352990`

Input  | Output
------------- | -------------
`45`  | `180000`

Input  | Output
------------- | -------------
`9999999`  | `801490`

- Lưu ý: Số tiền phải trả cho 1 số không âm.

# Bài 3 (Trung bình, chủ đề: mảng, class, constructor, getter,setter):
- Đề bài: tạo class Hacker có các thuộc tính sau:
  - Thuộc tính : tên, năm sinh, địa chỉ, sở thích.
  - Phương thức: HienThiThongTin()
  
a) 
- Yêu cầu: Tạo và hiển thị thông tin Hacker:
  - Hacker1: khởi tạo không có tham số, dùng setter để thiết lập thuộc tính, dùng sout + getter để hiện thị.
  - Hacker2: khởi tạo có 3 tham số truyền vào, gọi hàm HienThiThongTin().
  
b)
- Yêu cầu: Tạo một mảng, viết hàm để thực hiện:
  - Hiển thị thông tin Hacker có độ tuổi 18 (năm nay là 2019)
  - Hiển thị thông tin Hacker có chữ cái đầu tiên trong tên là chữ T (t)

# Bài 4 (Khó, chủ đề: kế thừa, class, ArrayList)
- Đề bài: Tạo 2 class PhoneBook kế thừa CustomerPhone để thực hiện bài toán sau:

CustomerPhone  |
------------- |
=====Thuộc tính===== |
`private String name`
`private int age`
`private String phone`
=====Phương thức==== |
`void ShowInfo()`

PhoneBook  |
------------- |
============Thuộc tính=========== |
`private ArrayList <CustomerPhone> PhoneBook`
============Phương thức========== |
`void AddCustomerPhone(CustomerPhone A)`
`CustomerPhone SearchByName(String name)`
`void ShowCustomerPhoneBookByName()`
`CusomerPhone SearchByAge(int age1,int age2)`
`void ShowCustomerPhoneBookByAge()`
`void ShowAllPhoneBook()`

- Yêu cầu: Tạo PhoneBook lưu trữ `n` CustomerPhone đồng thời sử dụng được các hàm void. Tạo constructor cho mỗi class.

- Chú thích thêm: 
  - `SearchByName(String name)` sẽ nằm trong `ShowCustomerPhoneBookByName()`.
  - `SearchByAge(int age1,int age2)` với age1,age2 nghĩa là từ age1-> age2 và class này nằm trong `ShowCustomerPhoneBookByAge()`.
  
## :warning: `Lưu ý:`
- Có 2 lựa chọn:
  - Làm bài 1,2,3
  - Làm bài 4

## :gift: Bonus
- Không có
>>>>>>> f32ab4e286ac612808934c62d9958495bb859aaa
# :skull: DEADLINE
Lớp thứ sáu  | Lớp chủ nhật
------------- | -------------
19h tối thứ 5  | 19h tối thứ 7
