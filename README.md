# patternprinting
Pattern printing using Java
// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the number of rows and columns");
        int r = sc.nextInt();
        int c = sc.nextInt();
        for(int i=r;i>=1;i--){
            for(int j=1;j<=i;j++){
                    System.out.print("*");
            }
                System.out.println();
        }
    }
}

Enter the number of rows and columns
6
6
******
*****
****
***
**
*

Pattern 2
Try programiz.pro
8
12345678
23456781
34567812
45678123
56781234
67812345
78123456
81234567

// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        Scanner sc= new Scanner(System.in);
        int r=sc.nextInt();
        for(int i=1;i<=r;i++){
            for(int j=i;j<=r;j++){
            System.out.print(j);
            }
            for(int k=1;k<=i-1;k++){
                System.out.print(k);
            }
            System.out.println();
        }
    }
}

Pattern printing 3

Try programiz.pro
Enter the number of rows
8
8
12345678
1      8
1      8
1      8
1      8
1      8
1      8
12345678

// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the number of rows");
        int r=sc.nextInt();
        int c=sc.nextInt();
        for(int i=1;i<=r;i++){
            for(int j=1;j<=c;j++){
                if(i==1 || i==r || j==1 || j==c){
                    System.out.print(j);
                }
                else{
                    System.out.print(" ");
                }
            }
                System.out.println();
        }
        
    }
}

Pattern 4

Try programiz.pro
7
1
12
123
1234
12345
123456
1234567

// Online Java Compiler
// Use this editor to write, compile and run your Java code online
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("Try programiz.pro");
        Scanner sc = new Scanner(System.in);
        int r=sc.nextInt();
        for(int i=1;i<=r;i++){
            for(int j=1;j<=i;j++){
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
