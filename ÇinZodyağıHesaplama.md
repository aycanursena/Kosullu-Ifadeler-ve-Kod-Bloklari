```
package KosulluIfadelerKodBloklari;
import java.util.Scanner;

public class CinZodyagiHesaplama {
    public static void main(String[] args) {
        Scanner veri = new Scanner(System.in);
        int dogumTarihi;
        String burc = "";

        System.out.print("Doğum tarihinizi giriniz :");
        dogumTarihi = veri.nextInt();

        if (dogumTarihi % 12 == 0){
            burc = "maymun";
        }else if (dogumTarihi % 12 == 1){
            burc = "horoz";
        }else if (dogumTarihi % 12 == 2){
            burc = "köpek";
        }else if (dogumTarihi % 12 == 3) {
            burc = "domuc";
        }else if (dogumTarihi % 12 == 4){
            burc = "fare";
        }else if (dogumTarihi % 12 == 5){
            burc = "öküz";
        }else if (dogumTarihi % 12 == 6){
            burc = "kaplan";
        }else if (dogumTarihi % 12 == 7){
            burc = "tavşan";
        }else if (dogumTarihi % 12 == 8){
            burc = "ejderha";
        }else if (dogumTarihi % 12 == 9){
            burc = "yılan";
        }else if (dogumTarihi % 12 == 10){
            burc = "at";
        }else if (dogumTarihi % 12 == 11){
            burc = "koyun";
        }
        System.out.println("Çin Zodyağı Burcunuz :" + burc);
    }
}
```
