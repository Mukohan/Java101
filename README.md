# Java101 www.patika.dev
java.util.Scanner;

public class Main {
    public static void main(String[] args) {
int mat;
        int fiz;
        int kim;
        int muz;
        int tur;
        int tar;
        Scanner inp = new Scanner(System.in);
        System.out.print("Matematik Notu:");
        mat = inp.nextInt();

        System.out.print("Fizik Notu:");
        fiz = inp.nextInt();

        System.out.print(" Kimya Notu:");
         kim = inp.nextInt();

         System.out.print("Müzik Notu:");
         muz = inp.nextInt();

         System.out.print("Türkçe Notu:");
         tur = inp.nextInt();

         System.out.print("Tarih Notu:");
         tar = inp.nextInt();

          int toplam = (mat + fiz + kim + muz + tur + tar);
          double sonuc = toplam / 6.0;
          System.out.println("Ortalama : " + sonuc);
          boolean kosul= sonuc >= 60;
          String gectimi = kosul ? "Sınıfı Geçti" : "Sınıfta Kaldı";
          System.out.println(gectimi);
