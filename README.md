# kdv.java
import java.util.Scanner;

  public class KDV
  public static void main(String[] args){
  double tutar 
  scanner inp = new Scanner(System.in);
	double Tutar, Vergili_Tutar, Vergi_Tutari;
	System.out.print("Ücret Tutarını Giriniz : ");
	Tutar = inp.nextDouble();
	Vergili_Tutar = Tutar + (Tutar*18/100);
	Vergi_Tutari = Vergili_Tutar - Tutar;
	System.out.println("KDV'li Tutar:" + Vergili_Tutar);
	System.out.println("KDV Oranı %18");
	System.out.print("KDV Tutarı " + Vergi_Tutari);	}	





