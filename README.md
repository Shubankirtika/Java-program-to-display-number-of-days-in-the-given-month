# Java-program-to-display-number-of-days-in-the-given-month
import.java.util.Scanner;
class NumOfDays
{
  public static void main(String args[])
  {
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter month Number:");
    int monthnumber;
    String monthString;
    monthnumber=sc.nextInt();
    switch(monthnumber)
    {
      case 1: monthString ="January";
              System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
              break;
      case 3: monthString = "March";
              System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
              break;
      case 5: monthString = "May";
              System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
              break;
      case 7: monthString = "July";
              System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
              break;
      case 8: monthString = "August";
              System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
              break;
      case 10: monthString = "October";
               System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
               break;
      case 12: monthString = "December";
               System.out.println(monthString+"\n"+ "Total number of days in the given month:31"); 
               break;
      case 4: monthString = "April";
              System.out.println(monthString+"\n" +"Total number of days in the given month:30"); 
              break;
      case 6: monthString = "June";
              System.out.println(monthString+"\n" +"Total number of days in the given month:30"); 
              break;
      case 9: monthString = "September";
              System.out.println(monthString+"\n" +"Total number of days in the given month:30"); 
              break;
      case 11: monthString = "November"; 
               System.out.println(monthString+"\n" +"Total number of days in the given month:30"); 
               break; 
      case 2:  monthString = "February";
               System.out.println(monthString+"\n"+ "Total number of days in the given month:28"); 
               break;
      default;
              System.out.println("Invalid month");
      break;
      }
    }
  }

