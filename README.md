# -ÜçgendeAlanBulanProgram
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner cikti = new Scanner(System.in);

        System.out.print("Yükseklği Giriniz: ");
        int h=cikti.nextInt();

        System.out.print("Taban Uzunluğunu Giriniz:");
        int a=cikti.nextInt();

        System.out.println("Üçgenin Alanı : " + a*h/2);
