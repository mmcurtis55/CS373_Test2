# Test 2 concepts
---
## Python concepts
- classes
```Python
class Ex:
```
- closures
```Python
  def outter(func):
    varr = "this"
    def inner(str):
      print(str)

    return inner #For a closure reutrn inner without ()
```
- constructors
```Python
  class Person:
    def __init__(name, age):
      self.name = name
      self.age = age
```
- decorators
```Python
  class debug_class :
    def __init__ (self, f) :
        self.f = f

    def __call__ (self, n) :
        print(self.f.__name__, ":", end=" ")
        print("input =", n, ";", end=" ")
        m = self.f(n)
        print("output =", m, ";")
        return m

  @debug_class
  def f3 (n) :
    return n + 1

  def test3 () :
    assert f3(2) == 3 # f3 : input = 2 ; output = 3 ;
```
  - [More about decorators](https://github.com/gpdowning/cs373/blob/master/examples/Decorators.py)
- operator overloading
- reflection
- regular expressions
- instance and class methods
- instance and class variables

---

## Python keywords
- self
- class
- def
- lambda
- self
- static method

---

## Relational Algebra concepts (and Python implementations)
- cross join
- natural join
- project
- select
- theta join

---

## SQL keywords
- create
- cross join
- drop
- group by
- having
- inner join
- natural join
- order by
- select
- show
- subqueries
- using
- where

---

## Java concepts
- abstract classes
- abstract methods
- class and static class variables
- Class.forName()
- Class.newInstance()
- ClassCastException
- ClassNotFoundException
- composition
- constructors
- dynamic binding
- IllegalAccessException
- inheritance
- instance and class methods
- instance and class variables
- InstantiationException
- interfaces
- reflection
- static binding

---

## Java keywords
- @override
- abstract
- catch
- class
- final
- interface
- private
- protected
- public
- static
- this
- throw
- try

---

## Refactorings
- extract method
- move method
- replace conditional with polymorphism
- replace temp with query
- replace type code with state/strategy
- replace type code with subclasses

---

## design patterns
- singleton
  - [Python singleton example](https://github.com/gpdowning/cs373/blob/master/examples/SingletonPattern.py)
- strategy
