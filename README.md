![Imgur](https://i.imgur.com/m0Nxl3L.png)

# Lesson 1.1: Combining Strings

## Objectives:

- Learn how to combine/concatenate strings and string variables.
- Learn about whitespace in Python strings.

---

## String Concatenation

Combining strings in Python is often called __string concatenation__ where the verb is __concatenate__. If you look for a definition of concatenate [here](https://www.lexico.com/en/definition/concatenate) or [here](https://www.merriam-webster.com/dictionary/concatenate), the definitions reference linking things together.

 youTo combine two strings in Python, the concatenation operator (`+`) is used. The `+` operator may look like an addition sign, and in fact it behaves like one with numeric data types. With the data type `str` or strings, the `+` operator combines them. 

To combine two strings , simply add `+` between the strings you want to concatenate. Try the code below __Example 1__ in the REPL:

#### Example 1

```python
print('Bob' + 'Ross')
```

The output is as follows:

```
BobRoss
```

Notice that __Python did not add whitespace between the strings__. To actually have a space between `'Bob'` and `'Ross'` , a `' '`it must be concatenated  between the two strings. Try the code below __Example 2__ in the REPL:

#### Example 2

```python
print('Bob' + ' ' + 'Ross')
```

The output is as follows:

```
Bob Ross
```

The same behavior is consistent with variables that point to string values. Try the code below __Example 3__ in the REPL:

#### Example 3

```python
first_name = 'Bob'
last_name = 'Ross'

print(first_name + last_name)
```

The output is as follows:

```
BobRoss
```

Just like the output of __Example 1__,  the two strings are run together without a space. A space must be concatenated between the two strings. Try the code below __Example 4__ in the REPL:

#### Example 4

```python
first_name = 'Bob'
last_name = 'Ross'

print(first_name + ' ' + last_name)
```

The output is as follows:

```
Bob Ross
```

Just as in the output of __Example 2__, the space is added between the strings for a more desirable output.



#### Example 5

```python
food1 = 'pizza'
food2 = 'sushi'
food3 = 'tacos'

print('My favorite foods are' + food1 + ',' + food2 + ', and' + food3 + '.')
```

```
My favorite foods arepizza,sushi, andtacos.
```



#### Example 6

```python
food1 = 'pizza'
food2 = 'sushi'
food3 = 'tacos'

print('My favorite foods are ' + food1 + ', ' + food2 + ', and ' + food3 + '.')
```



```
My favorite foods are pizza, sushi, and tacos.
```





#### Example 8

```python
food1 = 'pizza'
food2 = 'sushi'
food3 = 'tacos'
favorite_foods = food1 + ', ' + food2 + ', and ' + food3

print('My favorite foods are ' + favorite_foods + '.')
```



```
My favorite foods are pizza, sushi, and tacos.
```





#### Example 9

```python
food1 = 'pizza'
food2 = 'sushi'
food3 = 'tacos'
favorite_foods = 'My favorite foods are ' + food1 + ', ' + food2 + ', and ' + food3 + '.'

print(favorite_foods)
```



---

# Lab 1.1:  Combining Strings

Create the following variables and assign appropriate strings as the values of the variables with the `=` operator:

- `first_name`

- `last_name`

- `occupation`

- `city`

- `state`

  Using a single `print()` function, print the variables to match the possible outputs below:

```
Alice Smith is a(n) architect from Portland, Maine.
```

```
Oscar Johnson is a(n) pilot from Huntsville, Alabama.
```

__Hint:__ Concatenate the variables and strings to produce an output like the ones listed above. Remember to add a single space where appropriate to prevent the strings from running together. ___Do not forget the `,` between the city and state, and the `.` at the end of the sentence.___

## Bonus 1

Recreate the same program using three variables `name`, `occupation`, and `place` where:

- `name` is a concatenation of `first_name`, and `last_name`
- `occupation` is unchanged
- `place` is a concatenation of `city`, and `state` with a comma between them.

## Bonus 2

Recreate the same program using one variable `person` where:

- `person` is a concatenation of the whole sentence.



# Useful Links:

[![IMAGE ALT TEXT](http://img.youtube.com/vi/de7tDgQSUck/0.jpg)](https://youtu.be/de7tDgQSUck "Master Code Online: String Concatenation In Python")



[w3schools.com: Python String Concatenation](https://www.w3schools.com/python/gloss_python_string_concatenation.asp)

