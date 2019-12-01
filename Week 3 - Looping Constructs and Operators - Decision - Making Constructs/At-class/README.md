# Buổi 3: Câu lệnh rẽ nhánh, vòng lặp, hàm ,mảng cơ bản
## Nội dung bài học
- Bài này đều là những kiến thức cơ bản trong lập trình nên mình sẽ không nói kĩ quá mà để các bạn tự tìm hiểu thôi
  - Rẽ nhánh: [Xem tại đây](https://www.w3schools.com/java/java_switch.asp)
  - Vòng lặp: [Xem tại đây](https://o7planning.org/vi/11563/vong-lap-trong-java)
  - Hàm: [Xem tại đây](https://vietjack.com/java/phuong_thuc_trong_java.jsp)
  - Mảng: [Xem tại đây](https://o7planning.org/vi/11567/mang-array-trong-java)
## Tổng kết
- Bài này cần nắm chắc kiến thức nhất về phần hàm. Có 2 loại hàm:
  - Hàm trả về: là hàm để lưu kết quả sau khi làm một số công việc trong hàm ấy
```   
      int TinhTong(int a,int b)
      {
        return a+b;
      }
```
 -> Lúc này `TinhTong(int a,int b)` sẽ có giá trị là `a+b`
  - Hàm không trả về: hàm dùng để làm mọi công việc nhưng không lưu trữ giữ liệu
```   
    int TinhTong()
    {
      Scanner sc = new Scanner(System.in);
      int a,b;
      a = sc.NextInt();
      b = sc.NextInt();
      System.out.println(a+b);
    }
```
-> Lúc này `TinhTong()` không có giá trị, nó sẽ thực hiện những gì có trong hàm đó
  
