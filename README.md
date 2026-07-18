    // A simple method that adds two numbers and returns the result
    public static int addNumbers(int num1, int num2) {
        return num1 + num2;
    }

    public static void main(String[] args) {
        // Print a simple message to the console
        System.out.println("Hello, World!");

        // Loop to print numbers from 1 to 3
        for (int i = 1; i <= 3; i++) {
            System.out.println("Count: " + i);
        }

        // Call the custom method and store the result
        int sum = addNumbers(5, 10);
        System.out.println("The sum is: " + sum);
    }
}
