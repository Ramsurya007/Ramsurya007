import java.util.Scanner;

public class SumOfFiveIntegers {

  public static void main(String[] args) {
    Scanner input = new Scanner(System.in); 
    int sum = 0; 
    System.out.println("Please enter five integers:");
    for (int i = 0; i < 5; i++) {
      int number = input.nextInt(); 
      sum += number; 
    }
    System.out.println("The sum of the five integers is: " + sum);
  }
}
