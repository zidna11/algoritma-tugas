import java.util.Scanner;

public class kembalian {

    public static void main(String[] args) {
        Scanner inputan = new Scanner(System.in);
    System.out.print("Masukan (kg) telur yang dibeli ");
    Double KiloTelor = inputan.nextDouble();

    System.out.print("Masukan uang bayar ");
    Double UangBayar = inputan.nextDouble();

    Double HargaTelur = KiloTelor * 28000;
    Double Kembalian = UangBayar - HargaTelur;

    System.out.printf("uang kembalian : %.2f",Kembalian);

    inputan.close();

    }
}  

import java.util.Scanner;
public class lingkaran {


    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // Konversi suhu Celcius ke Fahrenheit
        System.out.print("Masukkan suhu dalam Celcius: ");
        double celcius = input.nextDouble();
        double fahrenheit = (celcius * 9/5) + 32;
        System.out.println("Suhu dalam Fahrenheit adalah: " + fahrenheit);

        // Menghitung keliling lingkaran
        System.out.print("Masukkan jari-jari lingkaran: ");
        double jariJari = input.nextDouble();
        double keliling = 2 * Math.PI * jariJari;
        System.out.println("Keliling lingkaran adalah: " + keliling);

        // Menghitung luas persegi panjang
        System.out.print("Masukkan panjang persegi panjang: ");
        double panjang = input.nextDouble();
        System.out.print("Masukkan lebar persegi panjang: ");
        double lebar = input.nextDouble();
        double luas = panjang * lebar;
        System.out.println("Luas persegi panjang adalah: " + luas);

        // Menghitung volume kubus
        System.out.print("Masukkan panjang sisi kubus: ");
        double sisi = input.nextDouble();
        double volume = Math.pow(sisi, 3);
        System.out.println("Volume kubus adalah: " + volume);

        input.close();

    }
}
