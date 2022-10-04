# 2D_array-input
 import java.util.Scanner;

class HelloWorld {

    public static void main(String[] args) {

     int[][] arr=new int [4][4];

     Scanner sc=new Scanner (System.in);

     System.out.println("enter x: ");

     int x= sc.nextInt();

     System.out.println("Enter y:");

     int y=sc.nextInt();

     for(int i=0; i<x; i++){

       for(int j=0; j<y; j++){

           System.out.print(arr[i][j]);

          }

          System.out.println();

     }

     

    }

}
