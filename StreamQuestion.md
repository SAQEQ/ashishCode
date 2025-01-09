
   1. Write a Java 8 program to find the distinct characters in a list of strings 
```java
        List<String> strings1 = List.of("apple", "banana", "cherry");
         System.out.println(strings1.stream().flatMapToInt(String::chars).mapToObj(x->(char) x).collect(Collectors.toSet()));

```