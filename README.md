# Single-level-Inheritence
Simple example of Single level inheritence
import java.util.*;

class Shape{
	int length;
	int height;
	
}	
class Triangle extends Shape{
	public void area(){
		System.out.println(0.5*length*height);
	
	}
}

class Main{
	public static void main(String[] args){
		Triangle t1 = new Triangle();
		Scanner sc = new Scanner(System.in);
		System.out.println("enter Triangle Length!");
		t1. length = sc.nextInt();
		System.out.println("enter Triangle Height!");
		t1. height = sc.nextInt();
		t1.area();
		

	}
}
