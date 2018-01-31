# Java Static Initializer Block

https://www.hackerrank.com/challenges/java-static-initializer-block

```java
static int B;
static int H;
static boolean flag = false;

static{
    Scanner sc = new Scanner(System.in);
    B = sc.nextInt();
    H = sc.nextInt();
    sc.close();

    if(B<=0 || H<=0) {
        System.out.println("java.lang.Exception: Breadth and height must be positive");
        flag = false;
    } else {
        flag = true;
    }
}
```