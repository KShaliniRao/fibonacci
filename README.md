//fibonacci
// Program to print the fibonacci series

package fibonacci;

public class fibonacci{

    public static void main(String[] args) {

        int n = 10, t1 = 0, t2 = 1;
        System.out.print("Fibonacci series: ");
        System.out.print("\n First " + n + " terms: ");

        for (int i = 1; i <= n; ++i)
        {
            System.out.print(t1 + "  ");

            int sum = t1 + t2;
            t1 = t2;
            t2 = sum;
        }
    }
}

OUTPUT=>

Fibonacci series: 
 First 10 terms: 0  1  1  2  3  5  8  13  21  34 
