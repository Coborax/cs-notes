---
tags: [SCO]
title: Inscance & class variables
created: '2020-09-01T07:06:41.537Z'
modified: '2020-09-01T07:21:58.302Z'
---

# Inscance & class variables

## Instance variables
- Exists on each instance of the class
- Should as a rule of thumb, instance variables should always be private. (To access them publicly one should use getters and setter methods)

### Java example
```java
public class Example {
  // Instance variable
  private int someInt = 10;

  // This can return different results for the different instances
  public int exampleMethod() {
    return someInt;
  }
}
```

## Class variables
- Exists on the class
- Same for all instances

### Java example
```java
public class Example {
  // Class variable
  static int someInt = 10;

  // This will return the same for all instances
  public int exampleMethod() {
    return Example.someInt;
  }
}
```
