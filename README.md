# Java-program-to-display-number-of-days-in-the-given-month
import.java.util.Scanner;
class NumOfDays
{
  public static void main(String args[])
  {
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter month Number:");
    int monthnumber;
    monthnumber=sc.nextInt();
    switch(monthnumber)
    {
    case 1:
    case 3:
    case 5:
    case 7:
    case 8:
    case 10:
    case 12:
    System.out.println("Total number of days in the given month:31");
       break;
    case 4:
    case 6:
    case 9:
    case 11:
    System.out.println("Total number of days in the given month:30");
      break;
    case 2:
    System.out.println("Total number of days in the given month:28");
      break;
      default;
    System.out.println("Invalid month");
      break;
      }
    }
  }
      
    
    
