import java.util.*;

public class ConditionsTask3 {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println("How old are you? ");
        int age = in.nextInt();
        boolean isAge = age <= 1 || age >= 120;
        if (isAge) {
            throw new IllegalArgumentException("false");
        } else {
            System.out.println("true");
        }
    }
}
