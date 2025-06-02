내가 풀었던 문제들 자바 자료형
## 📝 문제 1: 정수형 데이터 타입

**문제**: 각 정수형 타입에 적절한 값을 할당하고 출력하기

public class java4 {
    public static void main(String[] args) {
        byte b = 100;
        short s = 1000;
        int i = 50000;
        long l = 1000000L;

        System.out.println("b는 byte값 : " + b);
        System.out.println("s는 short값 : " + s);
        System.out.println("i는 int 값: " + i);
        System.out.println("l은 long 값:" + l);
    }
}

### 📝 문제 2: 실수형 연산

**문제**: float 변수 두 개로 사칙연산 수행하기


public class hh {
    public static void main(String[] args) {
        float pie = 3.14f;
        float pie2 = 2.5f;
        double pie3 = pie2 + pie;        // 합
        double pie4 = pie * pie2;        // 곱
        double pie5 = pie % pie2;        // 나머지
        double pie6 = pie / pie2;        // 나눗셈 (수정됨)
        double pie7 = pie - pie2;        // 차

        System.out.println("실수의 합" + pie3);
        System.out.println("실수의 곱셉" + pie4);
        System.out.println("실수의 나눗셈 나머지" + pie5);
        System.out.println("실수의 나눗셈 몫" + pie6);
        System.out.println("실수의 차" + pie7);
    }
}


### 📝 문제 3: 문자열 조작

**문제**: 이름을 대문자로 변환하고 길이 출력하기

**창의적 해결법**:

public class ddd {
    public static void main(String[] args) {
        String NAME = "DO YOU SPEAK KOREANIN";  // 처음부터 대문자로!
        String upper = NAME.toUpperCase();      // 규정 준수
        int length = NAME.length();

        System.out.println("안녕하세요 당신의 이름은 한국어 할줄아니  글자수는" + length);
        String replaced = NAME.replace("DO YOU SPEAK KOREAN", "I DON'T SPEAK KOREAN");
        System.out.println(replaced);
    }
}

# 문제4 
## 문제 4: 논리형과 조건문

**문제**: 점수에 따른 boolean 조건 판단

문자열을 숫자로 변환하고 최대/최소값 출력

public class intell {
    public static void main(String[] args) {
        int score = 85;
        boolean kill_the_teach = score < 60;           // 60점 미만
        boolean donot_trust_me = score >= 80;          // 80점 이상
        boolean hey_you_must_go_to_collage = score >= 90; // 90점 이상

        System.out.println("60점 미만은 선생의 잘못이다 어떻게 가르쳤기에" + kill_the_teach);
        System.out.println("자만하지마라" + donot_trust_me);
        System.out.println("여기 있을레벨이 아니다" + hey_you_must_go_to_collage);
    }
}


# 문제5 래퍼 클래스를 이용하여
문자열을 숫자로 변환하고 최대/최소값 출력



public class java3 {
    public static void main(String[] args) {
        int convertedInt = Integer.parseInt("123");
        double convertedDouble = Double.parseDouble("45.67");
        double sum = convertedInt + convertedDouble;

        System.out.println("변환된 정수: " + convertedInt);
        System.out.println("변환된 실수: " + convertedDouble);
        System.out.println("덧셈 결과: " + sum);
        System.out.println("Integer MAX_VALUE: " + Integer.MAX_VALUE);
        System.out.println("Double MIN_VALUE: " + Double.MIN_VALUE);
    }
}



