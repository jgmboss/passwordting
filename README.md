# import java.util.Scanner;

public class passwordting
{
    public static void main (String args[])
    {
        Scanner input = new Scanner(System.in);
        String password1;
        String password2;
        String correct = "false";

        while (correct.equals("false")){

            System.out.println("Please enter your password");
            password1 = input.nextLine();
            System.out.println("Please renter your password");
            password2 = input.nextLine();

            if (password1.equals(password2)){
                correct = "correct"; 
            }

            else{
                System.out.println("Passwords don't match"); 
            }

        }
        System.out.println("Passwords matched");

    }

}
