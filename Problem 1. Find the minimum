package Problem;

public class Problem_1 {
    private static int findMin(int[] arr, int n) {
        if (n == 1) {
            return arr[0];
        } else {
            int minSoFar = findMin(arr, n - 1);
            return Math.min(minSoFar, arr[n - 1]);
        }
    }

    public static int getMinimum(int[] arr, int n) {
        return findMin(arr, n);
    }
}
