
# EX 1A Print All Numbers 
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

---

## Algorithm:
1. Start the program.  
2. Import the `Scanner` class for input.  
3. Create a `Scanner` object.  
4. Read the integer value **N** from the user.  
5. Check if **N > 0**:  
   - If yes, use a `for` loop from 1 to N.  
   - Print each number followed by a space.  
6. If **N ≤ 0**, print an error message.  
7. Stop the program.  

---

## Program:
```
/*
Program to Print All Numbers from 1 to N
Developed by: Harish R
Register Number: 212224230085
*/
```
```java
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int N = sc.nextInt();

        if (N > 0) {
            for (int i = 1; i <= N; i++) {
                System.out.print(i + " ");
            }
        } else {
            System.out.print("Invalid input. N must be greater than 0.");
        }

        sc.close();
    }
}
```
## Output:
<img width="440" height="161" alt="image" src="https://github.com/user-attachments/assets/1b634080-211d-4751-9d13-e367e5ecf3aa" />



## Result:
The program successfully print all the numbers from 1 to N. 
