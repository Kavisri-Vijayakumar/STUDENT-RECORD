public class Student {
    private String name;
    private int rollNumber;
    private double marks;
    public Student(String name, int rollNumber, double marks) {
        this.name = name;
        this.rollNumber = rollNumber;
        this.marks = marks;
    }
    public void displayStudentDetails() {
        System.out.println("Student Name: " + name);
        System.out.println("Roll Number: " + rollNumber);
        System.out.println("Marks: " + marks);
    }
    public String getName() {
        return name;
    }
    public void setName(String name) {
        this.name = name;
    }
    public int getRollNumber() {
        return rollNumber;
    }
    public void setRollNumber(int rollNumber) {
        this.rollNumber = rollNumber;
    }
    public double getMarks() {
        return marks;
    }
    public void setMarks(double marks) {
        this.marks = marks;
    }
    public static void main(String[] args) { 
        Student student1 = new Student("Alice", 101, 89.5);
        Student student2 = new Student("Bob", 102, 75.0);
        System.out.println("Student 1 Details:");
        student1.displayStudentDetails();
        System.out.println(); 
        System.out.println("Student 2 Details:");
        student2.displayStudentDetails();
    }
}
output
Student 1 Details:
Student Name: Alice
Roll Number: 101
Marks: 89.5

Student 2 Details:
Student Name: Bob
Roll Number: 102
Marks: 75.0

