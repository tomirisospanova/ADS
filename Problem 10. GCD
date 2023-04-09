package Problem;

public class Problem_10 {
    public static int findGCD(int a, int b) {
        if (a == 0) {
            return b;
        }

        a = Math.abs(a);
        b = Math.abs(b);

        return findGCD(b, a % b);
    }
}
