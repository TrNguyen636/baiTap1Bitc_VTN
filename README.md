# baiTap1Bitc_VTN
 Java-OOP
import java.util.Scanner;


public class TestHello {
    public static void main(String[] args) 
    {
        //Ex1: In chương trình Hello word 
        System.out.println("Hello World");

        //Ex2: In danh sách số nguyên từ nhỏ tới cao 
        int soThuNhat = 1 ;
        int soThuHai = 2 ;
        int soThuBa = 3 ; 
        int soThuTu = 4 ; 
        int soThuNam = 5 ; 
        int soThuSau = 6 ; 
        System.out.println("So thu nhat" + soThuNhat );
        System.out.println("So thu hai:" + soThuHai);
        System.out.println("So thu ba:" + soThuBa); 
        System.out.println("So thu tu:" + soThuTu);
        System.out.println("So thu nam:" + soThuNam);
        System.out.println("So thu sau:" + soThuSau);
        
        //Ex3: Tính toán tử bất kì cộng trừ nhân chia sử dụng 2 biến 
        int a = 10;
        int b = 5;
        System.out.println("so thu nhat: " + a + "\nSo thu hai: " + b);
        int add = a + b;
        System.out.println("Tong: " + add);
        int subtraction = a - b;        
        System.out.println("Hieu: " + subtraction);
        int multiplication = a * b;
        System.out.println("Tich: " + multiplication );
        int divide = a / b;
        System.out.println("Thuong: " + divide);

        //Ex4: Hãy tính chu vi hình tròn và diện tích hình tròn 
        double radius = 3.5;
        double pi = 3.14159;
        double chuViHinhTron = 2 * pi * radius;
        double dienTichHinhTron = pi * radius * radius  ; 
        System.out.println("Chu vi hinh tron:" + chuViHinhTron + "\nDien tich hinh tron: " + dienTichHinhTron);

        //Ex5 :Nhập dữ liệu từ bàn phím hiện thị thông tin tên , tuổi , chuyên ngành 
        Scanner input = new Scanner(System.in);
        System.out.println("Vui long nhap ten cua ban");
        String ten = input.nextLine();
        System.out.println("Vui long nhap tuoi cua ban");
        int tuoi = input.nextInt();
        System.out.println("Vui long nhap chuyen nganh cua ban");
        String chuyenNganh = input.next();

        System.out.println("==============================================");
        System.out.println("Ten: " + ten);
        System.out.println("Tuoi: " + tuoi);
        System.out.println("Chuyen Nganh: " + chuyenNganh);
        
        // System.out.printf("%s: %.1f tuoi %, chuyen nganh: %.2f", ten, tuoi, chuyenNganh );


    }
}
