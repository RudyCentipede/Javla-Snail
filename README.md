import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        float h = sc.nextFloat();
        float a = sc.nextFloat();
        float b = sc.nextFloat();
        System.out.println((int)(1 + (h - b - 1) / (a - b)));
    }

}
