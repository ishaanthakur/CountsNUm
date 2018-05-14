public class CountNums {
    // A function that takes any number and counts how many times 
    // that number appears in an array.
    public static int countNums (int[] intarray, int n) {
        int count = 0;
        for (int i = 0; i < intarray.length; i++) {
            if(intarray[i] == n)
                count++;
        }
        return count;
    }

    // A function that counts the number of zeroes in an array.
    public static int countZeroes (int[] zeroarray) {
        int count = 0;
        for (int i = 0; i < zeroarray.length; i++) {
            if(zeroarray[i] == 0)
                count++;
        }
        return count;
    }

    public static void main(String[] args) {
        int[] test = {1,0,9,0,9};
        // Testing out the functions.
        System.out.println(countNums(test, 9));
        System.out.println(countZeroes(test));
    }
}

