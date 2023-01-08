```java

package homework1;

import java.util.Scanner;

public class homeWork1 {

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);


// 문제 1: 숫자 변수에 50을 입력하고 25 이상이면 "포인트 대상" 아니면 "포인트 대상이 아닙니다." 출력하기
		int point = 50;
		if (point >= 25)
			System.out.println("포인트 대상입니다.");
		else if (point < 25)
			System.out.println("포인트 대상이 아닙니다.");
		
		System.out.println("---------------------------------");
		
		
// 문제 2: 문자형 변수에 "자바"를 입력하고 자바가 아니면 "B교실, C교실입니다." 자바이면 "A교실입니다."라고 출력하기
		String java = "자바";
		if (java == "자바")
			System.out.println("A교실입니다.");
		else
			System.out.println("B교실, C교실입니다.");
		
		System.out.println("---------------------------------");
		
		
// 문제 3: 숫자 2개를 입력받아서 큰 숫자를 출력하기 (삼항연산자 사용하기)
		int num1 = sc.nextInt();
		int num2 = sc.nextInt();
		int resultBig = ((num1 > num2) ? num1 : num2);
		System.out.println(resultBig);
		
		System.out.println("---------------------------------");
		
	
// 문제 4: 숫자 3개를 입력받아서 작은 숫자를 출력하기 (삼항연산자 사용하기)
		int numA = sc.nextInt();
		int numB = sc.nextInt();
		int numC = sc.nextInt();
		int resultSmall = ((numA < numB && numA < numC) ? numA : (numB < numC) ? numB : numC);
		System.out.println(resultSmall);
```



