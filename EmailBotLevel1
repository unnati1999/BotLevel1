import java.util.*;
class EmailAdministration{
	 String fname;
	 String lname;
	 String Pwd;
	 int MailBoxCapacity = 100;
	 String Dept;
	public EmailAdministration(String fname, String lname, String Dept){
		this.fname = fname;
		this.lname = lname;
		this.Dept = Dept;
		System.out.println("------------------------------------------------------------");
		System.out.println("Email Created for: "+this.fname);
		this.Pwd = generatePwd(8);
	}
	private static String generatePwd(int length) {
      	String capitalCaseLetters = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
      	String lowerCaseLetters = "abcdefghijklmnopqrstuvwxyz";
      	String specialCharacters = "!@#$";
      	String numbers = "1234567890";
      	String combinedChars = lowerCaseLetters + capitalCaseLetters + specialCharacters + numbers;
      	Random random = new Random();
            char[] pwd = new char[length];

      	
      	String str = new String(pwd);
      	return str;
   }
       	   public void changePwd(String Pwd){
		 
   		this.Pwd = Pwd;
		 }
   public void showInfo(){
   		System.out.println("Full Name: "+fname+" "+lname);
   		System.out.println("Email Address: "+fname+"_"+lname+"@Company."+Dept+".com");
   		System.out.println("MailBoxCapacity: "+MailBoxCapacity);
   		System.out.println("Pwd: "+Pwd);
   }
}
public class Test
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    System.out.println("Enter your fname:");
	    String fname = sc.nextLine();
	    System.out.println("Enter your lname:");
	    String lname = sc.nextLine();
	    System.out.println("Enter your Dept:");
	    String dept = sc.nextLine();
		EmailAdministration em = new EmailAdministration(fname,lname,dept);
		em.showInfo();
		System.out.println("------------------------------------------------------------");
	}
}
