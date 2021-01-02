> Classes form the basis for all data types in python

## Identifiers:

- Each Identifier is associated with the memory address of the object it refers to

```python
temperature = 30
#temperature is associated to the memory address of the integer object 
```

- An identifier has no declared type, the object to which it refers to has a definite type.

## Instantiation:

- This is the process of creating a new instance of a class, the syntax invokes the constructor of a class

```python
class object():
		constructor()

#instantiation
a = object() -> points to the constructor of the object class

```

## Calling methods:

- One or more methods in a class can be referred to as "member functions"
- methods are invoked on the instance of a class with the dot(.) operator

```python
class obejct ----
		method1()

a.method1()
```

- A method that do not change the state of an object is an accessor
- A method that changes the state of an object is a mutator

## The bool class:

- Numbers evaluate to false if zero and true if non-zero
- Sequences and other container types like strings and lists evaluate to false if empty and true if not

## The List Class:

- A list is a referential structure because it stores a sequence of references to its elements

```python
lista = [1,2,3,4]
lista[0], references the first element in the list
```

- Lists are array-based sequences and are zero-indexed
- Python uses the [ ] characters to initiate a list
- A list() constructor produces an empty list by default, and any parameter passed to it is iterable

 

## The Tuple Class:

- The tuple class is immutable and it is initiated with a ( )
- If representing a single element in a tuple, then it needs a ',' comma to differentiate it from a square bracket

```python
a = (17) #is not a tuple
a = (17,) #is a tuple
```

## The str class

- It represents an immutable sequence of characters based on unicode international character set

## The set and frozenset classes

- The set class represents the mathematical notion of a set

> A collection of element without duplicates and inherent order to the elements.

The major advantage of a set is that it is highly optimized for checking whether a specific element is contained in the set.

Only instances of immutable types like int, float, strings are eligible to be element of a set

- It is possible to maintain a set of tuples but not a set of list or sets, because the tuples are immutable and list or set are mutable.
- Python use { } for sets initalization

An { } doesn't represent an empty set, but rather a dictionary. Rather we use the constructor set()

```python
a = set('hello')
{'h', 'e', 'l', 'o'}
```

## The dict class

- This represents a dictionary or mapping
- A dictionary is a rep of key and value pairs