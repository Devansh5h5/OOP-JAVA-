public class fibonacciseries{
public static void main(String[] args) {
    int a = 0, b = 1,n=10;

    System.out.print("Fibonacci (non-recursive): " + a + " " + b + " ");

    for (int i = 2; i < n; i++) {
        int c = a + b;
        System.out.print(c + " ");
        a = b;
        b = c;
    }
}
}
