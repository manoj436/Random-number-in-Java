# Random-number-in-Java
import java.util.Random;
class RandomNumber{
    public static void main(String[] args)  {
        Random num = new Random();
        
        int Start = 10000, End = 999999;
        int value = num.nextInt(End - Start) + Start;
        
        System.out.println(value); 
    }
}
	
