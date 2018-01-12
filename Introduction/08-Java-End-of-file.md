# Java End-of-file

https://www.hackerrank.com/challenges/java-end-of-file

```java
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input;
        int rows = 1;
        while(sc.hasNextLine()){
            input = sc.nextLine();
            System.out.printf("%d %s\n", rows,input);
            rows++;
        }
        sc.close();
    }
}
```