# crispy-telegram
import java.util.Scanner;
public class DetermineAge {
    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        System.out.println("Enter year of birth");
        int year=input.nextInt();
        System.out.println("Enter date of birth");
        int date= input.nextInt();
        System.out.println("Enter month of birth");
        int month= input.nextInt();
        // Take the positive outcome;
        int day=+-(25+date);
        int duration=(8+-month);
        int age = (2024-year);
        System.out.println("Days;"+ (+-day));
        System.out.println("Months;"+ (+-duration));
        System.out.println("Age;"+ age);
    }
}
