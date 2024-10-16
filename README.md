# python

Compound Data Types:

Tuple(tuple):

- these are similiar to list but they are immutable , meaning once they are created there contents cannot be changed.

- e.g coordinates = (10.0, 20.0)

Dictionary(dict):

these are are a collection of key-value pairs and each key must be unique and the values can be any data type.

![image](https://github.com/user-attachments/assets/18f00a2f-2885-4df3-888f-e3589f2be946)

name and age are the key values and the values that are assigned to it are data that can be of any type

Type Conversion

Implicit Type Conversion:

- Python automatically converts one data type to another when necessary. For example, adding an integer to a float results in a float.

![image](https://github.com/user-attachments/assets/1715d986-79c3-4f90-a0df-445f42832f84)

Explicit Type Conversion (Type Casting):

- You can manually convert one data type to another using functions like:
- int()
- float()
- str()
- list()

![image](https://github.com/user-attachments/assets/14584826-21d7-47bb-a68f-b728974bd13e)


Lists, tuples, dictionaries, sets (16 Ocotber 2024)

list 

- it is an ordered list collection of items that can hold a variety of data types
- they are mutable , meaning that they can change their contents after they are created.

  Key characterisctics:
  - order: items in a list are ordered and indexed , starting from 0
  - mutability: they can be modified by adding, removing or changin elements
  - Heterogeneous: they can contain elements of different data types.
 
  Operations

  - append() - to add items to the end of the list or you can use insert() to add to a specific position.
  - use indexing (e.g. list[0] forthe first item) or slicing (e.g. list[1:3] for a small list)
    

Libraries

what are they ? 
- libraries in pyhton are collections of pre-written code that you import into your projects to extend the functionality of you programs.
- 
Why Use NumPy and pandas?

NumPy: Ideal for numerical computations and working with large arrays and matrices.

pandas: Essential for data analysis and manipulation, especially when dealing with structured data like tables.


PANDA 

panda is a python library used for working with data sets. it has many Functions for analyzing, cleaning, exploring and manipulating data.

What is Series?
- it is like a column in a table.
- it is a one-dimensional array holding data of any data type.

  Dataframe - it is a two-dimensional data structure that holds data like a two-dimensio array or a table with rows and columns.

Labels

- With the <b>index</b> argument, you can name your own labels. 


DATAFRAMES
- it is a 2 dimensional data structure

- Pandas use the loc attribute to return one or more specified row(s)
- If you have a large DataFrame with many rows, Pandas will only return the first 5 rows, and the last 5 rows:
- use to_string() to print the entire DataFrame.

Loading Files into  a DataFrame
- A simple way to store big data sets is to use CSV files (comma separated files).
- CSV files contains plain text and is a well know format that can be read by everyone including Pandas.




