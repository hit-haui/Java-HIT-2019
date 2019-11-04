# Bài 1 (Easy):
Tạo class Person như bảng trên và thực hiện yêu cầu:

Person  |
------------- |
=====Thuộc tính===== |
`private String name`
`private int age`
`private String hobby`
`private String sex`
=====Phương thức==== |
Không có

- Trong class Person
  - Tạo getter, setter cho các thuộc tính.
- Tạo class RunMain có hàm main trong đó
  - Tạo ra 2 đối tượng Person SonNghien và Person TuBueDe (Phải import class Person vào class RunMain).
  - Dùng Setter truyền vào giá trị thông tin cho 2 đối tượng (Không phải nhập).
  - Hiển thị thông tin 2 đối tượng.
# Bài 2 (Easy):
Tạo class Dog và thực hiện yêu cầu:

Dog  |
------------- |
=========Thuộc tính======== |
`private String name`
`private int MP=100`
=========Phương thức======= |
`public void InputName(String name)`
`public void ShowMP()`
`public void Bark ()`

- Trong class Dog
  - Phương thức InputName: sẽ cho phép truyền tên vào. (hàm này sẽ giống như setter).
  - Phương thức ShowMP: hiển thị ra MP.
  - Phương thức Bark: sẽ in ra màn hình `Tên + sủa` (Lưu ý ko đặt tên trùng với các leader hoặc sp ko ăn án tử nhé :v), đồng thời mất 20 MP. Nếu chưa điền tên sẽ hiển thị `Xin lỗi bạn chưa điền tên`.
- Tạo class RunMain có hàm main trong đó
  - Tạo ra 1 đối tượng (Phải import class Dog vào class RunMain).
  - Cho đối tượng thực hiện 3 lần phương thức Bark(), sau mỗi lần sử dụng sẽ gọi ra phương thức ShowMP() để kiểm tra số MP còn lại
    - VD: a.Bark() -> a.ShowMP() -> a.Bark() -> a.ShowMP() -> ....
# Bài 3 (Normal):
Tạo class Student và class JavaClass với:

Student  |
------------- |
=====Thuộc tính===== |
`private String name`
`private String code`
`private int age`
=====Phương thức==== |
`public void InputInfo()`
`public void ShowInfo()`

JavaClass  |
------------- |
=====Thuộc tính===== |
`private Student stdList[]`
`private int ratingStar`
=====Phương thức==== |
`private void InputStudent()`
`private void ShowStudent()`
`public void InputClassInfo()`
`public void ShowClassInfo()`

- Trong class Student
  - Phương thức InputInfo: Nhập tất cả dữ liệu của Student.
  - Phương thức ShowInfo: Hiển thị tất cả thông tin của Student trên một dòng.
    - VD: "Tên: Thụ, mã sv: 2017602543, tuổi: 20"
- Trong class JavaClass
  - Phương thức InputStudent: Trong phương thức này có nhập n là số sinh viên trong lớp, dùng for để nhập từng thành viên trong lớp.
  - Phương thức ShowStudent: Sử dụng vòng for để hiển thị ra tất sinh viên trong lớp.
  - Phương thức InputClassInfo: Nhập tên leader, đánh giá chất lượng ratingStar cho lớp đồng thời gọi phương thức InputStudent.
  - Phương thức ShowClassInfo: Hiển thị tên leader và đánh giá ratingStar rồi gọi phương thức ShowStudent.
- Tạo class RunMain có hàm main trong đó
  - Tạo ra 1 đối tượng JavaClass.
  - Nhập và xuất ra class đó.

## :warning: `Lưu ý:`
- Có 2 cách sắp đặt class như dưới đây.

Newbie
![image](https://user-images.githubusercontent.com/52252046/67147697-34cd7200-f2c1-11e9-94ee-12dcd0d0bb17.png)
Professional
![image](https://user-images.githubusercontent.com/52252046/67147726-8ece3780-f2c1-11e9-86a2-12754b2900ee.png)

- Nhập và truyền là 2 kiểu khác nhau lưu ý để làm bài.
## :gift: Bonus
- Bạn nào làm tốt được nhận một chàng vỗ tay nồng nhiệt của cả lớp :)) 
# :skull: DEADLINE
Lớp thứ sáu  | Lớp chủ nhật
------------- | -------------
19h tối thứ 4  | 19h tối thứ 6
