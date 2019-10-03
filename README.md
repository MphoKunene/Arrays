# Arrays
//Write a program to initialize an integer array and print the sum and average of the array
public class ArrayP1 {

    public static void main(String[] args) {
        //declaring 
        int[]arr = {10,20,30,83};
        double sum = 0;
        double avg = 0;
        
         //start_value; end_value; increment_number
        for(int i = 0;i< arr.length; i++)
        {
            sum += arr[i]; //calculates
        }
        avg = sum/arr.length; //calculates
        System.out.println("The sum is: " + sum + "\nThe average is: " + avg);
        
    }
    
}
