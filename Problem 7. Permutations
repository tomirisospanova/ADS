package Problem;

public class Problem_7 {
    public static void printPermutations(String str) {
        printPermutationsHelper(str, "");
    }

    private static void printPermutationsHelper(String remaining, String current) {
        if (remaining.length() == 0) {
            System.out.println(current);
        } else {
            for (int i = 0; i < remaining.length(); i++) {
                char charToRemove = remaining.charAt(i);
                String newRemaining = remaining.substring(0, i) + remaining.substring(i + 1);

                String newCurrent = current + charToRemove;

                printPermutationsHelper(newRemaining, newCurrent);
            }
        }
    }
}
