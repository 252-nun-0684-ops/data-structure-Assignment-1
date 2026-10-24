import java.util.Scanner; // Imports Scanner for input

public class Task01 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in); // Creates input object
        int[] arr = new int[10]; // Declares an array of 10 integers

        // Takes input for all 10 elements
        for (int i = 0; i < 10; i++) {
            System.out.print("Enter number: ");
            arr[i] = sc.nextInt();
        }

        // Displays array elements in normal order
        System.out.println("Array elements:");
        for (int i = 0; i < 10; i++) {
            System.out.print(arr[i] + " ");
        }

        // Displays array elements in reverse order
        System.out.println("\nReverse order:");
        for (int i = 9; i >= 0; i--) {
            System.out.print(arr[i] + " ");
        }

        sc.close(); // Closes the input object
    }
}# data-structure-Assignment-1