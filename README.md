AIM: STUDY OF SET

ALGORITHM:
QUES1:
1.Start
2.Create a list of participant names
3.Convert the list into a set to remove duplicate names
4.Display the set of unique participants
5.Stop

QUES2:
1.Start
2.Create three sets containing subjects chosen by each student
3.Find the intersection of all three sets
4.Display the common subjects
5.Stop

QUES3:
1.Start
2.Create one set for Cricket Club students
3.Create one set for Football Club students
4.Find students present in both clubs using intersection
5.Find students present in only one club using symmetric difference
6.Display both results
7.Stop

QUES4:
1.Start
2.Create a set of all students
3.Create a set of present students
4.Subtract present students set from all students set
5.Display the absent students
6.Stop

QUES5:
1.Start
2.Create a set of valid course codes
3.Remove the discontinued course code using remove() or discard()
4.Display the updated set
5.Stop


THEORY:
A set in Python is a built-in data type used to store a collection of unique elements.
Sets do not follow any fixed order and do not allow duplicate values.
They are written using curly braces { }.

Nature of Set (Unordered and Unique):
A set stores multiple values in a single variable, but the elements are not stored in sequence. 
The order of elements may change every time the set is printed.
Sets automatically remove duplicate values, so the same element cannot appear more than once.
Because of this property, sets are very useful when uniqueness is required.

Accessing Elements and Data Types:
Since sets are unordered, indexing is not allowed and individual elements cannot be accessed using position numbers.
Attempting indexing results in an error. A set can store different data types such as integers, float values, strings, and boolean values together. 
In Python, True is treated as 1, so both cannot exist separately in the same set.

Modification of Sets:
Sets are mutable, which means elements can be added or removed after creation.
New elements can be added using the add() method. Existing elements can be removed using remove() or discard(). 
This makes sets flexible when working with changing data.

Set Operations (Main Application):
Sets are widely used to perform mathematical operations.
Union (|) combines elements from two sets,
Intersection (&) finds common elements,
Difference (-) removes elements of one set from another, and
Symmetric Difference (^) removes common elements and keeps only different ones.
These operations help in comparing and filtering data efficiently.

Frozen Set (Immutable Set):
A frozenset is a fixed or immutable version of a set. Once created, elements cannot be added or removed. 
Methods like add() and remove() do not work on a frozenset.
However, set operations such as union and intersection can still be performed on frozensets.

Practical Use of Sets:
Sets are commonly used in real-life problems such as removing duplicate participant names, 
finding common subjects chosen by students, identifying students present in multiple clubs, finding absent students, 
and removing invalid entries from a dataset.


CONCLUSION:
From this study, we understood that sets in Python are used to store unique elements in an unordered manner.
We learned how to create sets, add and remove elements, and perform different set operations like union, intersection, and difference. 
The concept of frozenset was also studied, which is an immutable form of a set.
Overall, sets are very useful for removing duplicates, comparing data, and solving real-life problems efficiently.
