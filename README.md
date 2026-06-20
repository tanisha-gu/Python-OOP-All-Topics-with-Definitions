# Python-OOP-All-Topics-with-Definitions

##  All Concepts Summary Table
 
| # | Concept | One-line Definition | Key Syntax |
|---|---------|---------------------|-----------|
| 1 | **Class & Object** | Blueprint → Real instance | `class Car:` / `car1 = Car()` |
| 2 | **Method & Self** | Function inside class; self = this object | `def method(self):` |
| 3 | **Inheritance** | Child reuses Parent's code | `class ElectricCar(Car):` |
| 4 | **Encapsulation** | Hide data, expose via methods | `self.__brand` + getter/setter |
| 5 | **Polymorphism** | Same method name, different behavior | Override `fuel_type()` in child |
| 6 | **Class Variable** | Shared value across all objects | `total_cars = 0` (outside `__init__`) |
| 7 | **Static Method** | Utility with no self/cls needed | `@staticmethod` |
| 8 | **Property Decorator** | Method accessed like an attribute | `@property` / `@x.setter` |
| 9 | **isinstance()** | Check object type with inheritance | `isinstance(obj, ClassName)` |
| 10 | **Multiple Inheritance** | Inherit from 2+ parent classes | `class HybridCar(Car, Electric):` |
 
---
 
##  Key OOP Principles (The 4 Pillars)
 
```
┌─────────────────────────────────────────────────────────┐
│                  4 PILLARS OF OOP                       │
├──────────────────┬──────────────────────────────────────┤
│ Encapsulation    │ Bundling data + hiding internals      │
│ Inheritance      │ Child class reuses parent class code  │
│ Polymorphism     │ Same interface, different behavior    │
│ Abstraction      │ Hiding complexity, showing essentials │
└──────────────────┴──────────────────────────────────────┘
```
