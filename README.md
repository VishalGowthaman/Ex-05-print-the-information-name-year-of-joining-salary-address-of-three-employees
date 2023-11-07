# Ex-05-print-the-information-name-year-of-joining-salary-address-of-three-employees
# Program
```
Developed By : Vishal Gowthaman K R
Reg No : 212221230123
```
```
public class Main{
    String name;
    int yearOfJoining;
    String address;

    public Main(String name, int yearOfJoining, String address) {
        this.name = name;
        this.yearOfJoining = yearOfJoining;
        this.address = address;
    }

    public void displayInfo() {
        System.out.println(name + "\t\t" + yearOfJoining + "\t\t\t" + address);
    }
    public void displayInfoo() {
        System.out.println(name + "\t\t\t" + yearOfJoining + "\t\t\t" + address);
    }

    public static void main(String[] args) {
        Main employee1 = new Main("Robert", 1994, "64C- WallsStreat");
        Main employee2 = new Main("Sam", 2000, "68D- WallsStreat");
        Main employee3 = new Main("John", 1999, "26B- WallsStreat");

        System.out.println("Name\t\tYear of joining\tAddress");
        employee1.displayInfo();
        employee2.displayInfoo();
        employee3.displayInfo();
    }
}

```
# Output
![image](https://github.com/Rohith-AIDS/Ex-05-print-the-information-name-year-of-joining-salary-address-of-three-employees/assets/94980736/a6eeeaec-1dd7-4e9d-95bc-2fd266418e13)
