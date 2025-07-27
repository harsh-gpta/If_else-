# If_else-
import java.util.Scanner;
public class project_1 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("welcome to my program");
        System.out.println("enter your name here");
        String name = sc.next();
        System.out.println();
        System.out.println("enter your age here");
        int age = sc.nextInt();
        System.out.println();
        int score = 0;
        System.out.println("QUESTION 1: CAPITAL OF RAJASTHAN");
        System.out.println();
        System.out.println("enter your answer here");
        String ans = sc.next();
        if (ans.equals("jaipur")){
            System.out.println("correct answer"+ name + " keep it up");
            score++;
            System.out.println("your score is "+score);
        }
        else{
            System.out.println("incorrect answer! " + name + "  keep it up");
            score--;
            System.out.println("your score is "+score);
        }
        System.out.println();
        System.out.println("QUESTION 2: PRIME MINISTER OF INDIA");
        System.out.println("enter your answer here");
        String ans2 = sc.next();
        if (ans2.equals("modi")){
            System.out.println("your answer is correct "+ name + " keep it up" );
            score++;
            System.out.println("your score is:" + score);
        }
        else {
            System.out.println("incorect answer " + name + " keep it up");
            score--;
            System.out.println("your score is:" + score);
        }
        System.out.println();
        System.out.println("Question 3: IN WHICH PLANET YOU");
        System.out.println("Entre your answer here");
        String ans3 =sc.next();
        if (ans3.equals("earth")){
            System.out.println("your answer is correct " + name + " keep it up");
            score++;
            System.out.println("your score is:" + score);
        }
        else{
            System.out.println("incorect answer " + name + " keep it up");
            score--;
            System.out.println("your score is:" + score);
        }
        System.out.println();
        System.out.println("OUESTION3: WHAT IS THE NATIONAL ANIMAL OF INDIA");
        System.out.println("enter your answer here");
        String ans4 = sc.next();
        if (ans4.equals("tiger")){
            System.out.println("your answer is correct " + name + " keep it up");
            score++;
            System.out.println("your score is:" + score);
        }
        else{
            System.out.println("incorect answer " + name + " keep it up");
            score--;
            System.out.println("your score is:" + score);
        }
        System.out.println();
        System.out.println("question5: national bird of india");
        String  ans5 = sc.next();
        if (ans5.equals("peacock")){
            System.out.println("your answer is correct " + name + " keep it up");
            score++;
            System.out.println("your score is:" + score);
        }
        else{
            System.out.println("incorect answer " + name + " keep it up");
            score--;
            System.out.println("your score is:" + score);

        }
        System.out.println();
        System.out.println("QUESTION 6: REPUBLIC DAY OF INDAI ");
        System.out.println("enter answer your here");
        String ans6 = sc.next();
        if (ans6.equals("26january")){
            System.out.println("your answer is correct " + name + " keep it up");
            score++;
            System.out.println("your score is:" + score);
        }
        else{
            System.out.println("incorect answer " + name + " keep it up");
            score--;
            System.out.println("your score is:" + score);
        }
        if (score>=4){
            System.out.println("congrats your brain is in the place");
        }
        else System.out.println("your brain is not brannving");
        }








}
