## Basics

- Always start with

```java
	public class "classname" {
	public static void main(String arugs[]){
	}
	}
```

- Print

```java
	System.out.println("helloworld");
	System.out.print("helloworld");
```

- Variable type (Data types)

	short
	int
	long
	float
	double
	char
	boolean

- Taking input

```java
import java.util.Scanner;
public class add2num{

public static void main(String arugs[]){
    Scanner name= new Scanner(System.in);
    int i = name.nextInt();
    int j = name.nextInt();
    int k = (i+j);
    System.out.println(k);
    name.close();
}

}
```
 
 
 same for all, except char
```java
char c = str.charAt(0);
```
Take the string `str` and **get the character at index 0** (the first character).

*char example*
```java
import java.util.Scanner;
public class char_data {
    public static void main(String arugs[]){
        Scanner ch = new Scanner(System.in);
        String strin= ch.nextLine();
        char c=strin.charAt(0);
        System.out.println(c);
        ch.close();
    }
}
```


- String
```java
String str = forstr.next();
```
Reads **one token** (word) from input.



```java
String str = forstr.nextLine();
```
Reads **the whole line** until you press **Enter**.


*String example*

```java
import java.util.Scanner;

public class string_char {
    public static void main(String arugs[]){
        Scanner forstr= new Scanner(System.in);
        // String str=forstr.next();

        String str=forstr.nextLine();
        System.out.println(str);
        forstr.close();
    }
}
```