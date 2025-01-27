# Compile-time
package main;
import.java.until.scanner;
public class Main {
public int addition(int x, int y) {
    return x + y;
  }
  public int addition(int x, int y, int z) {
    return x + y + z;
  }
  public double addition(double x, double y) {
    return x + y;
  }
    public static void main(String[] args) {
        Main number = new Main();
    int res1 = number.addition(22,44);
    System.out.println("Addition of two integers: " + res1);

    int res2 = number.addition(43,76);
    System.out.println("Addition of three integers: " + res2);

    double res3 = number.addition(45.15, 25.22);
    System.out.println("Addition of two doubles: " + res3);
    }
    
}

Output:
Addition of two integers: 66
Addition of three integers: 119
Addition of two doubles: 70.37
