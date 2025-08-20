# Machine-Learning-Advance-Python-Concepts
# Iterators
Iterators are objects that allow you to traverse through all the elements of a collection, one at a time. In Python, an iterator implements the iterator protocol, which consists of the __iter__() and __next__() methods.
Iterators are memory efficient as they don't store the entire collection in memory
They can only move forward through the collection
Once exhausted, they cannot be reused

# Generators
Generators are a simpler way to create iterators using a function syntax. They use the yield keyword to return values one at a time, pausing execution between calls.
More memory efficient than regular functions for large datasets
Maintain their state between calls
Can be created using generator functions or generator expressions

# Decorators
Decorators are a powerful way to modify or enhance functions without changing their actual code. They are essentially functions that take another function as an argument and return a modified function.
Allow for code reuse and separation of concerns
Can be chained (multiple decorators on a single function)
Can accept arguments themselves
