# Electricity-bill-
import java.util.Scanner;
public class electricitybill {

    public static void main(String[]args){

        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the no.of units consumed:");
        int units = sc.nextInt();
        double rate = 1.50;
        double billamount =units*rate;
        System.out.println("Electricity Bill Amount : Rs. " + billamount);
    }
}


OUTPUT:

Enter the no.of units consumed:250
Electricity Bill Amount : Rs. 375.0
