# Arithmetic Operators

|Operator|Description|
|--|--|
|`+`|Addition|
|`-`|Subtraction|
|`*`|Multiplication|
|`/`|Division|
|`%`|Modulus|

# Compound Arithmetic Operators

Shortcut the arithmetic assignment

## Binary operators
|Operator|Description|
|--|--|
|`+=`|Addition and assignment `var = var + value`| 
|`-=`|Subtraction and assignment `var = var - value`|
|`*=`|Multiplication and assignment `var = var * value`|
|`/=`|Division and assignment `var = var / value`|
|`%=`|Modulus and assignment `var = var % value`|

## Unary operators
|Operator|Description|
|--|--|
|`++`|`var = var + 1`|
|`--`|`var = var 1 1`|


```java
public class ArithmeticFun {
    public static void main(String[] args) {
        int a = 10;
        int b = 15;

        /*
          operators: +, -, *, /, % 
          operands a, b
        */
        
        // examples of BINARY operations
        int result = a + b;
        int difference= a -b;
        int product = a * b;
        int quotient = b / a;
        int remainder = b % a;

        // The output is concatenated
        System.out.println("result is " + result);
        System.out.println("diff is " + difference);
        System.out.println("product is " + product);
        System.out.println("quotient is " + quotient);
        System.out.println("remainder is " + remainder);

        result+= 20; //result = result + 20
        System.out.println("result is now " + result);

        //e.g. UNARY operations (it takes 1 operand)
        result++; //increment: result = result + 1
        System.out.println("result++ " + result);

        result--; // decrent: result = result - 1;
        System.out.println("result-- " + result);

        product *= 2; // product = product * 2
        System.out.println("product *= " + product);

        product /= 2; //product = product / 2
        System.out.println("result /= " + product);

    }
}
```
