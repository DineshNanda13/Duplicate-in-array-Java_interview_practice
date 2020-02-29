# Duplicate-in-array-Java_interview_practice
Java program to print duplicate elements in an array 

package duplicate;

/**
 *
 * @author Dinesh Nanda
 */

public class DuplicateArray {

    public static void main(String[] args) {
        
        int arr[] = {1, 2, 3, 4, 2, 7, 8, 8, 3};

        System.out.println("Duplicate elements in array are: ");

        for (int i = 0; i < arr.length - 1; i++) {
            for (int j = i + 1; j < arr.length; j++) {

                if (arr[i] == arr[j]) {
                    System.out.print(arr[j]+ " ");
                }
            }
        }
    } 
}
