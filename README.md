# 1010beecrowd
Beecrowd beginner problem 1010 solution with java code <br>
import java.util.Scanner; //<br>
import java.text.DecimalFormat; // <br>
public class Main {

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int code1 = s.nextInt();
        int units_product1 = s.nextInt();
        float price_perunit_1 = s.nextFloat();

        int code2 = s.nextInt();
        int units_product2 = s.nextInt();
        float price_perunit_2 = s.nextFloat();

        float calculate = (units_product1 * price_perunit_1) + (units_product2 * price_perunit_2);

        DecimalFormat f = new DecimalFormat("#.00");
        
        System.out.println("VALOR A PAGAR: R$ " + f.format(calculate) );
        
        
        
        s.close();
    }
}
