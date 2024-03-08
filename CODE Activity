using System;

namespace HelloWorld {

    class MainClass {

        public static void Main(string[] args) {

            Console.WriteLine("Welcome to the Coding Exercise!");

            Console.Write("Enter how many integers you are about to input: ");
            int lengthOfArray = Convert.ToInt32(Console.ReadLine());

            int[] nums = new int[lengthOfArray];
            Console.Write("Enter the target integer: ");
            int target = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Enter the integers one by one:");

            for (int i = 0; i < nums.Length; i++) {
                Console.Write($"Enter the integer for #{i + 1}: ");
                nums[i] = int.Parse(Console.ReadLine());
            }

            Console.WriteLine("The pairs of integers that sum up to the target are:");

            for (int i = 0; i < nums.Length; i++) {
                for (int j = i + 1; j < nums.Length; j++) {
                    if (nums[i] + nums[j] == target) {
                        Console.WriteLine($"[{nums[i]},{nums[j]}]");
                    }
                }
            }
        }
    }
}
