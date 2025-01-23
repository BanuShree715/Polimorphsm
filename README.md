# Polimorphsm
public class Main
{
  public int addition(int x, int y) 
  {
    return x + y;
  }
  public int addition(int x, int y, int z)
  {
    return x + y + z;
  }
  public double addition(double x, double y) 
  {
    return x + y;
  }
  public static void main(String[] args) 
  {
      Main number = new Main();
    int res1 = number.addition(77,90);
    System.out.println("Addition of two integers: " + res1);

    int res2 = number.addition(23,45,55);
    System.out.println("Addition of three integers: " + res2);

    double res3 = number.addition(70.15, 20.22);
    System.out.println("Addition of two doubles: " + res3);  
    }
}

Addition of two integers: 167
Addition of three integers: 123
Addition of two doubles: 90.37
BUILD SUCCESSFUL (total time: 0 seconds)

