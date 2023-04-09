package Problem;

public class Problem_2 {
    private static int findSum(int[] arr, int n) {
        if (n == 1) {
            return arr[0];
        } else {
            int sumSoFar = findSum(arr, n - 1);
            return sumSoFar + arr[n - 1];
        }
    }

    public static int getSum(int[] arr, int n) {
        return findSum(arr, n);
    }

    private static double findAverage(int[] arr, int n) {
        if (n == 1) {
            return arr[0];
        } else {
            int sum = findSum(arr, n);
            return (double) sum / n;
        }
    }

    public static double getAverage(int[] arr, int n) {
        return findAverage(arr, n);
    }
}
