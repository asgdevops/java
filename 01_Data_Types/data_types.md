# :book: Java Data Types

## Primitive

- Hold the value of interest directly.
  
|Name|Type|Size in bytes|
|--|--|:--|
|byte   |Integer|1|
|short  |Integer|2|
|int    |Integer|4|
|long   |Integer|8|
|float  |Real|4|
|double |Real|8|
|char   |Single character values|2 (16 bit units)|
|boolean|True or False values|1 or 2 depending on the platform|

## Reference types

- Hold the memory address of the object of interest.

```mermaid
flowchart LR
    a--->|reference to object|b
    subgraph String='Antonio'
      a[0xF2F1AC07] 
    end
    subgraph address 0xF2F1AC07
      b((("Antonio")))
    end
```

## Example:
```java
public class ConverstionFun {
    public static void main(String[] args) {
        double myDouble = 3.14;
        float myFloat = 3.14f; //narrowing/lossy conversion
        double yourDouble = myFloat; //widening/lossless conversion
    }//end main
}
```