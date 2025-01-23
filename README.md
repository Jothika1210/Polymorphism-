# Polymorphism-
package compiletimepolymorphism;

public class Compiletimepolymorphism{

  public int addition(int x, int y) 
 {
    return x + y;
  }
  public int addition(int x, int y, int z) {
    return x + y + z;
  }

  public double addition(double x, double y,double z) {
    return x + y + z;
  }
       public static void main(String[] args) {
          Compiletimepolymorphism number = new Compiletimepolymorphism();
        int res1= number.addition(111,333);
        System.out.println("Addition of two integers:"+res1);
        
        int res2 = number.addition(333, 666,999 );
        System.out.println("Addition of three integers:"+res2);
        
        double res3=number.addition(16.12,29.12,24.4);
        System.out.println("Addition of three doubles:"+res3);
        
            }
    
}

OUTPUT:
Addition of two integers:444
Addition of three integers:1998
Addition of three doubles:69.64
