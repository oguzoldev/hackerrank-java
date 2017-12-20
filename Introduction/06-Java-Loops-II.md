# Java Loops II

https://www.hackerrank.com/challenges/java-loops

```java
import java.util.*;
import java.io.*;
import java.math.*;
class Solution{
    public static void main(String []argh) {
        Scanner in = new Scanner(System.in);
        int t = in.nextInt();
        for(int i=0; i<t; i++) {
            int a = in.nextInt();
            int b = in.nextInt();
            int n = in.nextInt();
            int sonuc = a + b;

            for( int tekrar=1; tekrar<=n; tekrar++ ) {
                System.out.printf("%d ", sonuc);
                sonuc = sonuc + (int) Math.pow(2, tekrar) * b;
            }
            System.out.println("");
        }
        in.close();
    }
}
```