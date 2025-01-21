
class Student {
String name;
int age;

Student() {
    System.out.println("Default constructor called");
    name = "Unknown";
    age = 0;
}

Student(String name, int age) {
    System.out.println("Parameterized constructor called");
    this.name = name;
    this.age = age;
}

void displayDetails() {
    System.out.println("Name: " + name);
    System.out.println("Age: " + age);
}

}

public class Main {
public static void main(String[] args) {
Student s1 = new Student();
s1.displayDetails();

```    Student s2 = new Student("John Doe", 20);
    s2.displayDetails();
}

}


Output:

Default constructor called
Name: Unknown
Age: 0
Parameterized constructor called
Name: John Doe
Age: 20
# Constructor-
