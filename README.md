import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner s = new Scanner(System.in);
	    int r,q;
		System.out.println("Hi,Please enter your name:");
		String n = s.nextLine();
		System.out.println("Hey " +" " + n);
		System.out.println("=======MENU=======");
		System.out.println("1.Dal rice - 40/-" + "\n2.Hyderabad Biryani - 150/-" + "\n3.Curd rice - 30/-" + "\n4.Paav baaji - 120/-" + "\n5.Desserts");
		System.out.println("Select from the menu");
		int m = s.nextInt();
		switch(m)
		{
		   case 1:System.out.println("Plese enter quantity:");
		          q=s.nextInt();
		          System.out.println("You selected Dal rice pay " +" " +(q*40) +"/-");
		          r=s.nextInt();
		          if(r==(q*40))
		          {
		           System.out.println("Your Order placed");   
		          }
		           else
		          {
		              System.out.println("Enter valid amount");  
		          }
		          break;
		   case 2:System.out.println("Plese enter quantity:");
		          q=s.nextInt();
		          System.out.println("You selected Hyderabad Biryani pay " +" " +(q*150)+"/-");
		           r=s.nextInt();
		           if(r==(q*150))
		          {
		           System.out.println("Your Order placed");   
		          }
		          else
		          {
                   System.out.println("Enter valid amount");  
		          }
		           break;
		   case 3:System.out.println("Plese enter quantity:");
		          q=s.nextInt();
		          System.out.println("You selected Curd rice pay " +" " +(q*30)+"/-");
		           r=s.nextInt();
		           if(r==(q*30))
		          {
		           System.out.println("Your Order placed");   
		          }
		           else
		          {
		              System.out.println("Enter valid amount");   
		          }
		           break;
		   case 4:System.out.println("Plese enter quantity:");
		          q=s.nextInt();
		          System.out.println("You selected Paav baaji pay " +" " +(q*120)+"/-");
		           r=s.nextInt();
		           if(r==(q*120))
		          {
		           System.out.println("Your Order placed");   
		          }
		           else
		          {
		              System.out.println("Enter valid amount");  
		          }
		           break;
		   case 5:System.out.println("Plese enter quantity:");
		          q=s.nextInt();
		          System.out.println("You selected Desserts pay " +" " +(q*100)+"/-");
		           r=s.nextInt();
		           if(r==(q*100))
		          {
		           System.out.println("Your Order placed");   
		          }
		           else
		          {
		              System.out.println("Enter valid amount");  
		          }
		           break;     
		  default:System.out.println("Check once!!");         
		       
		}
		
		
	}
}
