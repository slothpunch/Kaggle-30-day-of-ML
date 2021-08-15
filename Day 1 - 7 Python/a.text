[Lists](https://www.kaggle.com/colinmorris/lists?utm_medium=email&utm_source=gamma&utm_campaign=thirty-days-of-ml&utm_content=day-5)

## **Interlude: objects**

I've used the term 'object' a lot so far - you may have even read that ***everything*** in Python is an object. What does that mean?

In short, objects carry some things around with them. You access that stuff using Python's dot syntax.

```python
x = 12
# x is a real number, so its imaginary part is 0.
print(x.imag)
# Here's how to make a complex number, in case you've ever been curious:
c = 12 + 3j
print(c.imag)

>>> 0
>>> 3.0
```

The things an object carries around can also include functions. A function attached to an object is called a method. (Non-function things attached to an object, such as imag, are called attributes).

```python
x.bit_length

>>> <function int.bit_length()>
```

To actually call it, we add parentheses:

```python
x.bit_length()

>>> 4
```

**Searching lists**

Use list.index(). 

```python
planets = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune']
planests.index('Earth')

>>> 2
```

If the value we are looking for doesn't exist in the list, an error occurs. To avoid it, use the in operator. 

```python
'Earth' in planets
'Calbefraques' in planets

>>> True
>>> False
```

## **Tuples**

Tuples are almost exactly the same as lists. They differ in just two ways.

**1.** The syntax for creating them uses parentheses instead of square brackets

**2.** They cannot be modified (they are *immutable*).

Tuples are often used for functions that have multiple return values.

For example, the `as_integer_ratio()` method of float objects returns a numerator and a denominator in the form of a tuple:

```python
x = 0.125
x.as_integer_ratio()

>>> (1, 8)
```

These multiple return values can be individually assigned as follows:

```python
numerator, denominator = x.as_integer_ratio()
print(numerator / denominator)

>>> 0.125
```
