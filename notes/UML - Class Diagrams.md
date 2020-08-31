---
attachments: [Clipboard_2020-08-30-20-26-34.png, Clipboard_2020-08-31-14-05-52.png]
tags: [SDE]
title: UML - Class Diagrams
created: '2020-08-30T18:25:57.819Z'
modified: '2020-08-31T12:07:54.597Z'
---

# UML - Class Diagrams

## Anatomy of a UML class
- Three versions of crab
- More qualified = more notations = more information

![class anatomy](@attachment/Clipboard_2020-08-30-20-26-34.png)

### Properties
- Represents structural features of a class
- Appears in two distinct notations
  - Attributes
    - Simple datatypes
  - Associations
    - Variable points to an object
- **Full syntax:** visibility name: type
  - **Example:** - wormsEaten: int

### Operations
- Operations are the actions that a class can do (Bescribes the behaviour of the class)
- Normally one would not show operations that manipulates properties in a simple way
  - Like getters and setters
- **Full syntax:** visibility name(parameter list): return type
  - **Example:** + switchImage(): void

### Examples from class
#### Diagram
```mermaid
classDiagram
class Teacher{
  - name: String
  + age: int
  + teach(): void
  + getGrade(amountOfChocolate: int): int
}
```
#### Code
```java
public class Teacher {
  private String name;
  public int age;

  public void teach() { ... }
  public int getGrade(int amountOfChocolate) { ... }
}
```
#### Greenfoot wombat example
![](@attachment/Clipboard_2020-08-31-14-05-52.png)
