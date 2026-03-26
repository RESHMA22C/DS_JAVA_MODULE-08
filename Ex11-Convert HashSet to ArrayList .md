# Ex11 Convert HashSet to ArrayList in Java
## AIM:
To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
## Algorithm
1.Start and create an empty HashSet.

2.Insert all the required integers into the HashSet.

3.Create an ArrayList and pass the HashSet to its constructor.

4.Store all elements of the HashSet into the ArrayList.

5.Display the elements of the ArrayList.
  

## Program:
```
/*
Program to To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.
Developed by: Reshma C
RegisterNumber:  212223040168

import java.util.*;

public class HashSetToArrayList {

    public static ArrayList<Integer> convertToArrayList(HashSet<Integer> set) {
        ArrayList<Integer> list = new ArrayList<>(set);
        return list;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        HashSet<Integer> set = new HashSet<>();
        for (int i = 0; i < n; i++) {
            int num = sc.nextInt();
            set.add(num);
        }

        ArrayList<Integer> list = convertToArrayList(set);
        System.out.println("ArrayList contents:");
        for (int num : list) {
            System.out.print(num + " ");
        }
        sc.close();
    }
}
*/
```

## Output:

<img width="524" height="550" alt="image" src="https://github.com/user-attachments/assets/e9194978-e48b-433a-ad27-d79f62e5da3d" />


## Result:
The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList
