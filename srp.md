# SRP
>Single Responsibility Principle
- One of the SOLID Principles
- States each entity/function should have a single responsibility only
- These principles are applicable for all programming paradigm be it Functional, Object-Oriented.
- In OOPS-Encapsulation concept, we ensure that Single Responisibility Principle is followed. 
- As part of Encapsulation, we create classes and objects. The classes should follow SRP i.e. each class should have a single responsibility. Also, the class name should be such     that, it should state the responsibility of the class.
- Thus, at design time, while creating classes and defining role for them, we consider SRP.
- Example- UI creation- Have 3 roles, presentation, business, data. All 3 roles cannot be defined within a single class. Thus we have MVC, MVVM pattern which have differentiated     View,Model, ViewModel so that each role is defined properly. 
- Issues we face, when SRP is not followed- God class or Brain Method
