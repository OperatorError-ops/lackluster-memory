# Data Types Reference

## Here are the most common data types you'll use in Python:

### Integer
A whole number without decimals, for example, 10 or -5.

```python
my_integer_var = 10
print('Integer:', my_integer_var) # Integer: 10

cat > lessons/Data_Types_Reference.md << 'EOF'
# Data Types Reference

## Here are the most common data types you'll use in Python:

### Integer
A whole number without decimals, for example, 10 or -5.

```python
my_integer_var = 10
print('Integer:', my_integer_var) # Integer: 10
my_float_var = 4.50
print('Float:', my_float_var) # Float: 4.5
my_string_var = 'hello'
print('String:', my_string_var) # String: hello
my_boolean_var = True
print('Boolean:', my_boolean_var) # Boolean: True
my_set_var = {7, 'hello', 8.5}
print('Set:', my_set_var) # Set: {7, 'hello', 8.5}
my_dictionary_var = {'name': 'Alice', 'age': 25}
print('Dictionary:', my_dictionary_var) # Dictionary: {'name': 'Alice', 'age': 25}
my_tuple_var = (7, 'hello', 8.5)
print('Tuple:', my_tuple_var) # Tuple: (7, 'hello', 8.5)
my_range_var = range(5)
print('Range:', my_range_var) # Range: range(0, 5)
my_list = [22, 'Hello world', 3.14, True]
print(my_list) # [22, 'Hello world', 3.14, True]
my_none_var = None
print('None:', my_none_var) # None: None
my_var_1 = 'Hello world'
my_var_2 = 21

print(type(my_var_1)) # <class 'str'>
print(type(my_var_2)) # <class 'int'>
my_integer_var = 10
print(type(my_integer_var))  # <class 'int'>

my_float_var = 4.50
print(type(my_float_var))  # <class 'float'>

my_string_var = 'hello'
print(type(my_string_var))  # <class 'str'>

my_boolean_var = True
print(type(my_boolean_var))  # <class 'bool'>

my_set_var = {7, 'hello', 8.5}
print(type(my_set_var))  # <class 'set'>

my_dictionary_var = {'name': 'Alice', 'age': 25}
print(type(my_dictionary_var))  # <class 'dict'>

my_tuple_var = (7, 'hello', 8.5)
print(type(my_tuple_var))  # <class 'tuple'>

my_range_var = range(5)
print(type(my_range_var))  # <class 'range'>

my_list = [22, 'Hello world', 3.14, True]
print(type(my_list)) # <class 'list'>

my_none_var = None
print(type(my_none_var))  # <class 'NoneType'>
isinstance('Hello world', str) # True
isinstance(True, bool) # True
isinstance(42, int) # True
isinstance('John Doe', int) # False

Then commit it:

```bash
git add lessons/Data_Types_Reference.md
git commit -m "Add comprehensive data types reference guide"
git push origin main
