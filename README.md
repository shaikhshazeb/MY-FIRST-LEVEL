//question ( add two nuber using input from the user)
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("taking input from the user");
        Scanner s=new Scanner(System.in);
        System.out.println("enter the number 1");
        int a=s.nextInt();
        System.out.println("enter the number 1");
        int b=s.nextInt();
        int sum=a+b;
        System.out.println("adding of two numbers");
        System.out.println(sum);
    }
}

//out put 
java -cp /tmp/MYw6mhD0EH Main
taking input from the userenter the number 1
22
enter the number 1
33
adding of two numbers
55


// student percentage using input from the user



import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("taking input from the user");
        Scanner s=new Scanner(System.in);
        int total=100;
        System.out.println("enter the number marks");
        int a=s.nextInt();
        System.out.println("enter the number marks");
        int b=s.nextInt();
        System.out.println("enter the number marks");
        int c=s.nextInt();
        System.out.println("enter the number marks");
        int d=s.nextInt();
        System.out.println("enter the number marks");
        int e=s.nextInt();
        int sum=a+b+c+d+e;
        System.out.println(sum);
        float percentage=sum*100/500;
        System.out.println("your percentage is =" +percentage);
        }
}

//output

java -cp /tmp/MYw6mhD0EH Main
taking input from the user
enter the number marks
23
enter the number marks
44
enter the number marks
54
enter the number marks
34
enter the number marks
98
253
your percentage is =50.0

//question (given the answer)



class HelloWorld {
    public static void main(String[] args) {
        int a=10;
        if(a==11)
        
             System.out.println("i am 11");
        
        else
        
             System.out.println("i am not 11");
        
    }
}

//output

java -cp /tmp/SMy7i9nbzm HelloWorld
i am not 11

//question(to find out the day of the week)

import java.util.Scanner;
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("enter your case");
        Scanner sc=new Scanner(System.in);
        int week=sc.nextInt();
        switch(week){
            case 1:
                System.out.println("SUNDAY");
                break;
              case 2:
                System.out.println("MONDAY");
                break;
                case 3:
                System.out.println("TUESDAY");
                break;
                case 4:
                System.out.println("WEDNESDAY");
                break;
                case 5:
                System.out.println("THURSDAY");
                break;
                case 6:
                System.out.println("FRIDAY");
                break;
                case 7:
                System.out.println("SATURDAY");
                break;
                default :
                System.out.println("sorry not found");
    
        }
    }
}

//output
java -cp /tmp/0C8tnNsawZ HelloWorld
enter your case
9
sorry not found
java -cp /tmp/0C8tnNsawZ HelloWorld
enter your case
5
THURSDAY

// question(print 1 to 10 natural number )

class HelloWorld {
    public static void main(String[] args) {
        int i=1;
        while(i<=10){
        System.out.println(i);
        i++;
    }
 }
}

//output

java -cp /tmp/0zzYM556mB HelloWorld
1
2
3
4
5
6
7
8
9
10
//question(print first n natural numbers using do while loops)



class HelloWorld {
    public static void main(String[] args) {
      int a=1;
      do{
          System.out.println(a);
          a++;
          
     }while(a<=10);
    
 }
}

//output

java -cp /tmp/0zzYM556mB HelloWorld
12
3
4
5
6
7
8
9
10
//question(print natural numbers in reverse order)



class HelloWorld {
    public static void main(String[] args) {
     
     for(int i=5;i!=0;i--){
         System.out.println(i);
     }
          
    
    
 }
}
//output

java -cp /tmp/0zzYM556mB HelloWorld
5
4
3
2
1
//question(print the design)

class HelloWorld {
    public static void main(String[] args) {
   int n=4;
   for(int i=n;i>0;i--){
       for(int j=0;j<i;j++){
    System.out.print("*");
      }
  System.out.print("\n");
      }
   }
}

//output

java -cp /tmp/ONGYufE269 HelloWorld
****
***
**
*
lass HelloWorld {
    public static void main(String[] args) {
        int n=4;
        for(int i=n;i>0;i--){
            for(int j=0;j<i;j++){
                 System.out.print("*");
            }
        System.out.print("\n");
        }
            
    }
}

java -cp /tmp/8DZtRb8sZW HelloWorld
****
***
**

class HelloWorld {
    public static void main(String[] args) {
        int n=1;
        for(int i=n;i<5;i++){
            for(int j=0;j<i;j++){
                 System.out.print("*");
            }
        System.out.print("\n");
        }
            
    }
}

java -cp /tmp/8DZtRb8sZW HelloWorld
*
**
***
****
//question (sum of n even numbers )

class HelloWorld {
    public static void main(String[] args) {
       
       int sum=0;
       int n=4;
       for(int i=0;i<n;i++){
           sum= sum+ (2*i);
       }
           System.out.print("sum of even numbers  : ");
            System.out.println(sum);
    }
}

//output  java -cp /tmp/8DZtRb8sZW HelloWorld
sum of even numbers  : 12

//question(print 10 table)


class HelloWorld {
    public static void main(String[] args) {
        int n=10;
        for(int i=1;i<=n;i++){
            System.out.printf("%d X %d = %d",n,i,n*i);
        }
        System.out.println("\n");
        System.out.println("your table is ready");
    }
}

//output

java -cp /tmp/fGBe7g1SQn HelloWorld
10 X 1 = 10
10 X 2 = 20
10 X 3 = 30
10X 4 = 40
10 X 5 = 50
10 X 6 = 60
10 X 7 = 70
10 X 8= 80
10 X 9 = 90

your table is ready

//question(factoral of a given number)
class HelloWorld {
    public static void main(String[] args) {
       int n=10;
       int i=1;
      int factorial=1;
      
      while(i<=n){
          factorial *= i;
          i++;
      }
    
         System.out.println(factorial);
    }
}

//output

java -cp /tmp/E1lWydqeqW HelloWorld
3628800

