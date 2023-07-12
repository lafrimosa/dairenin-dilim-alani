import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
     int r, a;

        Scanner girdi = new Scanner(System.in);

         System.out.println(" dairenin yarıçapını giriniz: ");
         r= girdi.nextInt();

         System.out.println(" merkez açısının ölçüsünü giriniz: ");
         a = girdi.nextInt();


        double pi =3.14;
        double dilim = (pi * (r * r) * a) / 360;
        

        System.out.println("Daire diliminin alanı: " + dilim);




            }


    }
