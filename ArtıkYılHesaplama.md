```
package KosulluIfadelerKodBloklari;
import java.util.Scanner;

public class ArtikYilHesaplama {
    public static void main(String[] args) {
        Scanner veri = new Scanner(System.in);
        int yil;

        System.out.print("Yıl :");
        yil = veri.nextInt();

        if ((yil % 4 == 0 && yil % 100 != 0)) {
            System.out.println(yil + " bir artık yıldır!");
        }else if (yil % 100 == 0 && yil % 400 == 0){
            System.out.println(yil + " bir artık yıldır!");
        }else
            System.out.println(yil + " bir artık yıl değildir!");
    }
}
```
