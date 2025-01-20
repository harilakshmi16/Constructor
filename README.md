# Constructor
Constructor

class Student {
    String name;
    int rollNumber;

    Student(String name, int rollNumber) {
        this.name = name;
        this.rollNumber = rollNumber;
    }

    public void display() {
        System.out.println("Name: " + name);
        System.out.println("Roll Number: " + rollNumber);
    }
}

public class ConstructorExample {
    public static void main(String[] args) {
        Student student = new Student("John", 101);
        student.display();
    }
}

Output

Name: John  
Roll Number: 101
