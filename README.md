# java-program
import java.util.*;
class s1
{
    public static void main(String[]args)
    {
    Scanner a = new Scanner(System.in);
    System.out.println("Enter your base number");
    int base = a.nextInt();

    System.out.println("Enter your power number");
    int power = a.nextInt();

    int answer = power(base,power);
    
    System.out.println("Answer is"+answer);
    }
    static int power(int base , int power)
    {
        int answer = 1;

        for(int i=1 ; i<=power; i++)
        {
            answer = answer*base;
        }
        return answer;
    }
}    
