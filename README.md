
сдесь я сделал таблицу умножения и когда вы напишете число программа выдаст таблицу умножения с любым числом которое вы выдали. код вышел на самом деле простой и быстрый


import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
int u;
Scanner sc = new Scanner(System.in);
        System.out.println("напиши мне число с которым хочешь таблицу умножения ");
        boolean results = true;
        u = sc.nextInt();
        if( results == true ) {
            System.out.println("1 * " + u + " = " + 1 * u);
            System.out.println("2 * " + u + " = " + 2 * u);
            System.out.println("3 * " + u + " = " + 3 * u);
            System.out.println("4 * " + u + " = " + 4 * u);
            System.out.println("5 * " + u + " = " + 5 * u);
            System.out.println("6 * " + u + " = " + 6 * u);
            System.out.println("7 * " + u + " = " + 7 * u);
            System.out.println("8 * " + u + " = " + 8 * u);
            System.out.println("9 * " + u + " = " + 9 * u);
            System.out.println("10 * " + u + " = " + 10 * u);

        }

    }
}
