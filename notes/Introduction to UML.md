---
attachments: [Clipboard_2020-08-30-20-06-18.png, Clipboard_2020-08-30-20-06-58.png, Clipboard_2020-08-30-20-07-29.png, Clipboard_2020-08-30-20-08-38.png]
tags: [SDE]
title: Introduction to UML
created: '2020-08-30T17:58:16.390Z'
modified: '2020-08-30T18:25:32.687Z'
---

# Introduction to UML
- **U**nified **M**odelling **L**anguage
- Family of different graphical notations (You can make different diagrams for how a software system functions)
  - Sketch of a system (How a system should work)
  - Blueprint (How is  the system implemented) (Made after the system has been developed)
- Mainly aimed at OOP
- Can be used to generate code from UML, but it can be **janky**
- UML can be used before or after making a system (Forward/Reverse engineering)
- A common language everyone can understand
- UML can make it easier to get an overview of big code bases

## Different types of diagrams

### Activity diagram
![activity diagram](@attachment/Clipboard_2020-08-30-20-06-58.png)
### Sequence diagram
![sequence diagram](@attachment/Clipboard_2020-08-30-20-07-29.png)
### Class diagram
- Describes different kind of objects, classes and static relationsships
- Diagram over the code base
- Class diagrams are the backbone of UML
- Can be used to...
  - ...document the classes in the system we are making
  - ...illustrate our design considerations
  - ...read about software development
  - ...read design patterns
  - ...write reports
![class diagram](@attachment/Clipboard_2020-08-30-20-08-38.png)

## Class diagrams - A few tips
- Don't overdo it, keep it simple (It should be able to communicate, what you are thinking)
  - Create a model when making a tricky part of the system
  - Don't have many obsolete forgotten models
- Conceptual class diagrams (Helps understand the language of a business)
