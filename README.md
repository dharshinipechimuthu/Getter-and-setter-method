# Getter-and-setter-method
class Student {
    private int id;
    private String name;
    private double grade;
    public void setId(int id) {
        this.id = id;
        }
    public int getId() {
        return id;
    }
    public void setName(String name) {
        this.name = name;
    }
    public String getName() {
        return name;
    }
    public void setGrade(double grade) {
        this.grade = grade;
    }
    public double getGrade() {
        return grade;
    }
    public void displayDetails() {
        System.out.println("Student ID: " + id);
        System.out.println("Student Name: " + name);
        System.out.println("Student Grade: " + grade);
    }
}

public class StudentManagement {
    public static void main(String[] args) {
        Student student = new Student();
        student.setId(101);
        student.setName("Alice");
        student.setGrade(88.5);
        System.out.println("Student Details (Using displayDetails method):");
        student.displayDetails();
        System.out.println("\nStudent Details (Using getter methods):");
        System.out.println("Student ID: " + student.getId());
        System.out.println("Student Name: " + student.getName());
        System.out.println("Student Grade: " + student.getGrade());
    }
}
---

 Output

Student Details (Using displayDetails method):
Student ID: 101
Student Name: Alice
Student Grade: 88.5

Student Details (Using getter methods):
Student ID: 101
Student Name: Alice
Student Grade: 88.5
----
