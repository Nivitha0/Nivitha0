import java.util.Scanner;
class EmployeeDetails{
public static void main(String args[]){
Scanner Scanner = new Scanner (System.in);
String [] []  employee_Details = new String [3][5];
for (int i=0;i<3;i++)
{
System.out.println("Enter details for employee " + (i+1)); 
System.out.println ("Employee Id");
employee_Details[i][0]=Scanner.nextLine();
System.out.println("Employee Name"); 
employee_Details[i][1]=Scanner.nextLine(); 
System.out.println("Designation");
employee_Details[i][2]=Scanner.nextLine();
System.out.println("Experience");
employee_Details[i][3]=Scanner.nextLine();
System.out.println("Salary");
employee_Details[i][4]=Scanner.nextLine();
}
System.out.println("\n Employee details:"); 
for (int j=0;j<3;j++)
{
System.out.println("Employee"+(j+1)+":");
System.out.println("Employee Id"+employee_Details[j][0]);
System.out.println("Employee name:"+employee_Details[j][1]);
System.out.println("Designation:"+ employee_Details[j][2]);
System.out.println("Experience:"+employee_Details[j][3]);
System.out.println("Salary:" + employee_Details[j][4]);
System.out.println();
}
}
}



