# again

import java.util.Scanner;

public class Main {

    public static void main(String[] args){
        Scanner in = new Scanner(System.in);
        int q = 0;
        int bin = 0;
        int mod = 0;

        dec = in.nextInt();

        while ( dec!=0 ) {
            mod = q % 2;
            q /= 2;
            bin = (10*bin)+mod;
        }
        System.out.println(bin);
    }


}
