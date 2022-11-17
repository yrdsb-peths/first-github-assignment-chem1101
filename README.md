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
    
    public Student(String fName, String lName, int grade)
    {
        firstName = fName;
        lastName = lName;
        gradeLevel = grade;
    }
    
    public String toString()
    {
        return firstName + " " + lastName + " is in grade: " + gradeLevel;
    }
}
