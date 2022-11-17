# Welcome to our GitHub classroom!

Do the following to Complete this assignment:

1. Begin editing this file by clicking the 'pen' symbol above.

2. Enter your First Name: Chinechem 

3. Enter your favourite animal: Red Panda

4. Now click the green 'commit changes' button at the bottom.

5. Done!

public class Student
{
    private String firstName;
    private String lastName;
    private int gradeLevel;
    
    public Student(String 2Name, String lName, int grade)
    {
        firstName = 2Name;
        lastName = lName;
        gradeLevel = grade;
    }
    
    public String toString()
    {
        return firstName + " " + lastName + " is in grade: " + gradeLevel;
    }
}

public void run()
    {
        Student chem = new Student("chem", "ugo", 11);
        
        System.out.println(chem);
    }
