public class LogicApplication {
    public static void main(String[] args){
        int age = 16;
        int height = 165;
        int money = 15000;
        boolean hasGuardian = true;  // 보호자 동반 여부 (문제에서 true로 가정)

        // 각 조건별로 확인
        boolean ageHeightOK = (age >= 12 && height >= 140);
        boolean moneyOK = (money >= 10000);

        // 최종 입장 조건: (나이키 조건 OR 보호자 동반) AND 돈 조건
        boolean canEnter = (ageHeightOK || hasGuardian) && moneyOK;

        System.out.println("나이키 조건: " + ageHeightOK);
        System.out.println("보호자 동반: " + hasGuardian);
        System.out.println("돈 조건: " + moneyOK);
        System.out.println("입장 가능: " + canEnter);
    }
}

복습 1
