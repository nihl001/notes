# Python:

## Modules:
						
Any Python file is a module (.py) that is meant to be imported ( if it is meant to be executed is a script).


## Package:
						
A package is a directory of Python modules containing an additional __init__.py file, can be nested to any depth (subdirectories with modules and __init__).

	
## Numbers:

    0o10	           octal, prefixed by 0o (zero and a lowercase "o" or uppercase "O")
    0xA0F	           hexadecimal, prefixed either by "0x" or "0X".
    0b101010	   binary, prefixed by a "0", followed by a "b" or "B":


##Operators:

    /	           "true division", 5/3 results in 1.6666
    //	           "floor division", 5//3 results in 1
    |	           bitwise Or
    &	           bitwise And
    ^	           bitwise XOR
    ~		   bitwise negation
    **		   exponentiation


## Strings:

* There exists no character type in Python. A character is simply a string of size one. 

* Strings are immutable.


### Operators:

    +	           concatenation
    *	           repetition
    [i]	           indexing
    [i:j]	   	   slicing
    [::n]	   	   step ( [begin: end: step] )
    len(s)	   	   size
    ==	   	   comparison	
    <	   	   lexicographical less than
    > 	   	   lexicographical bigger than


## List Methods:

    .append()          add an element to the end of the list
    .extend()          add all elements of a list to another list, also operator "+=" (never use "l1 = l1 + l2")
    .insert()          insert an item at the defined index (.insert(index, object))
    .remove()          removes an item from the list
    .pop()             removes and returns an element at the given index, last by default
    .clear()           removes all items from the list
    .index()           returns the index of the first matched item. ValueError will be raised, if the value is not present.
    .count()           returns the count of number of items passed as an argument
    .sort()            sort items in a list in ascending order
    .reverse()         reverse the order of items in the list
    .copy()            returns a copy of the list

    [start:end]        slice operation
    [-Index]           from the end
    [::-1]             return list in reverse orden
    in                 if element in list (also "not in")
    +                  concatenation