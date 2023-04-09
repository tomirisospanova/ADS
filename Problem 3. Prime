package Problem;

public class Problem_3 {
    private static boolean isPrime(int n, int divisor) {
        if (n <= 1) {
            return false;
        }
        if (divisor > Math.sqrt(n)) {
            return true;
        }
        if (n % divisor == 0) {
            return false;
        }
        return isPrime(n, divisor + 1);
    }

    public static boolean checkPrime(int n) {
        return isPrime(n, 2);
    }
}
