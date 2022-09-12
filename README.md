# Hipotenus-ve-Alan
import java.util.Scanner;

public class Hipoenüs {
    public static void main(String[] args) {
        //degiskenler

        int a,b, d ;
        double c;

        //scanner ve verileri al
        Scanner girilenler = new Scanner(System.in);
        System.out.print(" kısa kenar ");
        a = girilenler.nextInt();

        System.out.print(" uzun kenar ");
        b = girilenler.nextInt();

        c = Math.sqrt((a*a)+(b*b));
        System.out.println(" hipotenüs uzunluğu"  + c);

         d = (a*b/2);
        System.out.println(" Alan " + d );
