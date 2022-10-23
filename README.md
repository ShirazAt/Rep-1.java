# Rep-1.java

import java.util.Scanner;

class Main {
  public static void main(String[] args) {
    Scanner in = new Scanner(System.in);
    char userin;
    //String ans;
    System.out.println("enter grade");
    userin = in.next().charAt(0);
    switch (userin){
      case 'A': case 'B': case 'C':
        System.out.println("good");
      case 'D':
        System.out.println("bad");

      default:
        System.out.println("incorrect");
    }
  }
}
   
