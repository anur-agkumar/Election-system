# Election-system
package Method;

import java.util.Scanner;

public class prime2 {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int num = in.nextInt();
        find(num);
        // System.out.println(num);
    }

    static void find(int num) {
     //  while(num>0) {
           int count = 0;
           for (int i = 2; i * i <= num; i++) {
               int temp = num % i;
               count++;

           }
           if (count > 1) {
               System.out.println("not prime");

           } else if (count <= 1) {
               System.out.println("prime ");

           }
        //if(num==0){break;}
       }
    //}

}
