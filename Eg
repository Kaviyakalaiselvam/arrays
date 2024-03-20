import java.util.Scanner;

public class OddEvenSeparate {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter the starting number: ");
        int start = scanner.nextInt();
        System.out.print("Enter the ending number: ");
        int end = scanner.nextInt();
        
        int oddCount = (end - start) / 2 + (start % 2 == 1 || end % 2 == 1 ? 1 : 0);
        int evenCount = (end - start) / 2;
        int[] oddNumbers = new int[oddCount];
        int[] evenNumbers = new int[evenCount];
        int oddIndex = 0, evenIndex = 0;
        for (int i = start; i <= end; i++) {
            if (i % 2 == 0) {
                evenNumbers[evenIndex] = i;
                evenIndex++;
            } else {
                oddNumbers[oddIndex] = i;
                oddIndex++;
            }
        }
        
        System.out.print("Odd numbers: ");
        for (int odd : oddNumbers) {
            if (odd != 0)
                System.out.print(odd + " ");
        }
        
        System.out.println();
        
        System.out.print("Even numbers: ");
        for (int even : evenNumbers) {
            if (even != 0)
                System.out.print(even + " ");
        }
    }
}
