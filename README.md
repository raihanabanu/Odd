
public class Odd {
	public static void main(String[] args) {
		int x=Integer.parseInt(args[0]);
		int y=2;
		int k=(x%y);
		if(k==0)
		{
			System.out.println("The given Number"+x+"is even");
		}
		else
		{
		System.out.println("the given Number"+x+"is odd");	
			
		}
	}
}
