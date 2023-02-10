# Relational Operators

Compare values and return True or False (boolean)

|Operator|Description|
|--|--|
|`>`|Greater than|
|`>=`|Greater or equal to|
|`<`|Less than|
|`<=`|Less than or equal to|

Equality operators
|Operator|Description|
|--|--|
|`==`|Equal to| 
|`!=`|Not equal to|

Example: 
```java
public class RelationalFun {
    public static void main(String[] args) {
        boolean myBool = true;
        boolean yourBool = false;
        int myAge = 50;
        int yourAge = 20;
        int bobsAge = 20;

        String myName = "Antonio";
        String yourName = "John";

        System.out.println("myBool is " + myBool);
        System.out.println("yourBool is " + yourBool);

        // relational operations
        boolean ageComparison = myAge > yourAge;
        System.out.println("myAge > yourAge?: " + ageComparison);

        ageComparison = yourAge > bobsAge;
        System.out.println("yourAge > bobsAge?: " + ageComparison);

        ageComparison = yourAge == bobsAge;
        System.out.println("yourAge == bobsAge?: " + ageComparison);

        ageComparison = yourAge != bobsAge;
        System.out.println("yourAge != bobsAge?: " + ageComparison);

        boolean nameComparison = myName.equals(yourName);
        System.out.println("do names match ?: " +  nameComparison);

        int currentAge = 50;

        boolean isGreater21 = currentAge >= 21 ;

        System.out.println("currentAge >= 21?: " + isGreater21);

    }//end main
}
```