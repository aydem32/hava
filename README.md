import java.util.Scanner;

public class etkinlik {
    public static void main(String[] args) {

        Scanner inp = new Scanner(System.in);
        int sicaklik;
        System.out.print("Sicaklik değerini giriniz:");
        sicaklik = inp.nextInt();
        if (sicaklik < 5) {
            System.out.println("Kayak Yapabilirsin");
        } else if (sicaklik >= 5 && sicaklik < 15) {
            System.out.println("Sinemaya Gidebilirsin");
        } else if (sicaklik >= 15 && sicaklik <25) {
            System.out.println("Pikniğe Gidebilirsin");
        } else if (sicaklik >= 25) {
            System.out.println("Yüzmeye Gidebilirsin");
        }

    }
}
