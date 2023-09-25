//# kdv-hesaplama
//java ile kdv hesaplama
import java.util.Scanner;

public class kdv_hesaplama {
    public static void main ( String[]args){
        double tutar, kdvOran= 0.18, kdvTutar ,kdvliTutar;
        Scanner input = new Scanner(System.in);
        System.out.print ("Ücret tutarı giriniz: ");
        tutar = input.nextDouble();

        kdvTutar = tutar * kdvOran;
        kdvliTutar = tutar + kdvTutar;

        System.out.println("kdvsiz tutar:" + tutar);
        System.out.println("kdv oranı : " + kdvOran);
        System.out.println("kdv tutarı: " + kdvTutar);
        System.out.println("kdv'li tutar:" + kdvliTutar);

    }
}
