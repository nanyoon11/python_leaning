# python_leaning

## Advanced Numbers


## Hexadecimal
Using the function hex() you can convert numbers into a hexadecimal format:
eg. hex(246)

## Binary
Using the function bin() you can convert numbers into their binary format.
eg. bin(1234)


## Exponentials
The function <code>pow()</code> takes two arguments, equivalent to ```x^y```.  With three arguments it is equivalent to ```(x^y)%z```, but may be more efficient for long integers.
eg. pow(3,4)


## Absolute Value
The function abs() returns the absolute value of a number. The argument may be an integer or a floating point number. If the argument is a complex number, its magnitude is returned.
eg. abs(-3.14)

## Round
The function <code>round()</code> will round a number to a given precision in decimal digits (default 0 digits). It does not convert integers to floats.
eg. round(3,2)

## Advanced Strings
s = 'hello world'
s.capitalize()
s.upper()
s.lower()
s.count('o')
s.find('o')
s.center(20,'z')
'hello\thi'.expandtabs() ##The expandtabs() method will expand tab notations \t into spaces:
s.split('e')
s.partition('l')
s.endswith('o') ##Another method is endswith() which is essentially the same as a boolean check on s[-1]


## Advanced Sets
s = set()
s.add(1)
s.clear() **removes all elements from the set
sc = s.copy()  **returns a copy of the set. Note it is a copy, so changes to the original don't effect the copy.
s.difference(sc)





