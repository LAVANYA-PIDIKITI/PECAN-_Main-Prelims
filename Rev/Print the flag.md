# Print the flag
Have a look at the code. I can see the flag sort of, however, the flag seems to be broken into different parts. Can you help me put it together?
```java
public class Main{
	public static void main(String[] args){
		String C = "our_a_b_c";
		String A = "pecan{jus";
		String D = "_s}";
		String B = "t_print_y";

		A + B + C + D
	}
}
```
# Solution
Execute the code and you get the flag
```java

public class Main{
	public static void main(String[] args){
		String C = "our_a_b_c";
		String A = "pecan{jus";
		String D = "_s}";
		String B = "t_print_y";

		System.out.printf(A + B + C + D);
	}
}
```
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/68e2bc8e-0013-43c7-83c2-6bccdb0659d6)
