# Encapsulation

Encapsulation in Java means making instance variables private and creating public getters and setters to them. Why are they useful? Setter can be used to check the value before assigning it to the instance variable. It allows to discard all inappropriate values and keep our code working. Setter can also be used to manipulate the passed data before assignment (rounding floating point values). Getter can be used to manipulate the value of an instance variable before returning it to the caller or to produce a side effect (logging to a file or a console). It's better to create getters and setters to instance varaibles which are supposed to be manipulated outside even if there are no limitations to the values of these variables initially. They can appear later and the code which uses your code will be safe.

## An example of encapsulation

~~~java
class Employee {
  private String name;
  private int salary;

  public String getName() {
    return name;
  }

  public void setName(String aName) {
    name = aName;
  }

  public int getSalary() {
    return salary;
  }

  public void setSalary(int aSalary) {
    salary = aSalary;
  }
}
~~~

    #java #encapsulation #getter #setter
