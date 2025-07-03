import java.util.Scanner;

public class atm 
{ public static void main(String[] args) {
    int balance =1000;
         int pin = 9999;
        Scanner scan = new Scanner(System.in);

        System.out.print("Enter your pin number: ");
        int PIN = scan.nextInt();

        if (PIN == pin) {
            while (true) {
                System.out.println("atm options");
                System.out.println("1. Check Balance");
                System.out.println("2. Deposit");
                System.out.println("3. Withdraw");
                System.out.println("4. Exit");
                System.out.print("Choose an option: ");
                int option = scan.nextInt();

                switch (option) {
                    case 1:
                     
                        System.out.println("Your account  balance is " + balance);
                        break;
                    case 2:
                        System.out.print("Enter deposit amount ");
                        int  deposit = scan.nextInt();
                       balance += deposit ;
                       
                        System.out.println("Deposit successfulyyyyyyyyy");
                        break;
                    case 3:
                        System.out.print("Enter withdrawal amount ");
                        int withdraw = scan.nextInt();
                        if(withdraw <= balance){
                        
                        
                            balance -= withdraw;
                            System.out.println(withdraw + "rupess debited");
                        System.out.println("withdraw successful");
                    }
                        break;
                    case 4:
                        System.out.println("thank you for visting");
                        return;
                        
                    default:
                        System.out.println("try again");
                }
            }
        } else {
            System.out.println("not verifird password");
        }
    }
}
