# 2020-06-26


package hello;

//import java.lang.*;

public class HelloJava {  //파일명과 동일한 클래스

	public static void main(String[] args) { // 실행의 시작 메인 메소드(method)
		System.out.println("Hello, Java");
		System.out.println("안녕, 자바"); //syso입력후, ctrl+space
		
	}

}
//주석(설명문, 비실행문)
//한줄주석
/* 
 */ //영역주석





package basicJava;

public class Hello1 {

	public static void main(String[] args) {
	
		/*
		 [문제]
		 basicJava프로젝트를 생성 후 
		 Hello1 클래스를 생성하여 결과 출력하기
		 
		 [결과]
		 Bye, C
		 
		 Bye, C++
		 
		 Hello, Java!

		 */
		
		System.out.println("Bye, C");
		System.out.println(); // 쌍따옴표를 넣어도 되고 안 넣어도 됨.
		// 또는 System.out.println("Bye, C\n"); 문자열 끝에 \n을 붙이면 엔터(newline)
		// 또는 System.out.println("~~~" + "\n");
		System.out.println("Bye, C++");
		System.out.println();
		System.out.println("Hello, Java!");
		
	} // main end

}



package day01;

public class Hello1 {

	public static void main(String[] args) {
		System.out.println("문자열 출력");
		System.out.println("A");
		System.out.println("ABC");
		System.out.println(1);
		System.out.println("1");
		System.out.println(1+2);		// (결과) 3    '+' 덧셈연산자
		System.out.println("1" + "2");  // (결과) 12   '+' 연결연산자
		System.out.println("저의 나이는 " + 20 + "살입니다");
		
		int age = 20; // '=' : assign or store ;  =/= equal 
		System.out.println("저의 나이는 " + age + "살입니다");
		age = 25; 	  // 변수의 대입문 (배정문,저장)
		System.out.println("저의 나이는 " + age + "살입니다");
		// age = age + 1;
		age += 1;
		// age++;
		// ++age;
		System.out.println("저의 나이는 " + age + "살입니다");
		
	}

}



package day01;

public class Variable {
	public static void main(String[] args) {
//		변수(variable) : Memory, 값(value)을 저장하는 공간
//		상수(costant) : 항상 똑같은 수, 변함 없는 수, value
//		ctrl+/ 주석
		System.out.println(123);		//일백이십삼(정수상수)
		System.out.println("123");		//일이삼(문자열상수)
		System.out.println(123+1);
		System.out.println("123+1");
		System.out.println("123" +  1); // 이 때의 '+'는 문자열 연결 연산자
		
/*
 * 정수형 상수 : +1, 3, 5, 3, ...
 * 실수형 상수 : +3.14,-3.14, ...
 * 		단정도형 실수 : 3.14f(4byte)
 * 		배정도형 실수 : 3.14 (8byte)
 * 문자형 상수 : 'a', 'A', '1', '+', ...
 * 문자열형 상수 :"Hello", "Hi", "화이팅", "A", ...
 * 논리형 상수 : true, false
 * 
 * 
 * -
 * 
 * 1. 변수 선언문; (자바의 경우 최초 선언시 초기화 해야만한다.)
 *        자료형 변수이름 ; 
 *     ex) int   age = 0;
 *     
 *     
 * 2. 변수대입(배정,할당)문; 
 * 	         변수이름 = 값;
 *    ex) age = 20;
 *    
 *    #변수이름 규칙 : 영문대문자 또는 소문자 또는 숫자 $, _ 는 사용가능
 *                 -숫자로시작할 수 없음
 *                 -변수명 사용불가
 *                 -특수문자 사용불가
 *                 
 *     
 *
 */
		
		
	}
	
}
