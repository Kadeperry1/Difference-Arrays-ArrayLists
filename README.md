# Difference-Arrays-ArrayLists
Explains the difference between Array and Arraylist in Java and gives examples
import java.util.ArrayList;
import java.util.Arrays;

class Main {
    public static void main(String[] args) {
 // Initializes an array of what I have eaten today
 String foodToday[] = {"Rice", "Eggs", "Chicken", "Toast"};
 System.out.println(Arrays.toString(foodToday));
 
 // Initializes an arraylist of what I have eaten today
 ArrayList<String> foodToday1 = new ArrayList<String>(Arrays.asList());
 
 // Allows us to add our food as we go instead of having to initizalize a new Array
 
 foodToday1.add("Rice");
 foodToday1.add("Eggs");
 foodToday1.add("Chicken");
 foodToday1.add("Rice");
 foodToday1.add("Toast");
 System.out.println(foodToday1);
    }
}
