import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);

		float a, b;
		char x;

		System.out.print("Enter first nomber: ");
		a = scan.nextFloat();
		System.out.print("Enter operation: ");
		x = scan.next().charAt(0);
		System.out.print("Enter second nomber: ");
		b = scan.nextFloat();

		switch (x) {
			case '+':
				System.out.println((a+b));
				break;
			case '-':
				System.out.println((a-b));
				break;
			case '*':
				System.out.println((a*b));
				break;
			case '/':
				System.out.println((a/b));
				break;
			default:
				System.out.println("You'r sucker!");
		}
    }
}