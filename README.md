# Debug
Debugs
package Aemo;

public class Largest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 int[] array = {10, 20, 30, 40, 50, 60, 70, 80, 90};

	        // Call the function to find the largest element
	        int max = findLargest(array);

	        // Print the largest element
	        System.out.println("The largest element in the array is: " + max);
	    }

	    // Function to find the largest element in an array
	    public static int findLargest(int[] array) {
	        int max = array[0]; // Assume first element is the largest

	        // Loop through the array
	        for (int i = 1; i < array.length; i++) {
	            if (array[i] > max) {
	                max = array[i]; // Update max if current element is larger
	            }
	        }

	        return max; // Return the largest element
	    }
	

	}


