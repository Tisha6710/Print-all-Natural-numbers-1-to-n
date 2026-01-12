# Print-all-Natural-numbers-1-to-n
package Recursion;

import java.util.Scanner;

public class printNum {
    static void printIncresing(int n){
        if(n==1){
            System.out.println(n);
            return;
        }
        printIncresing(n-1);
        System.out.println(n);
    }

    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        printIncresing(n);
    }
}
