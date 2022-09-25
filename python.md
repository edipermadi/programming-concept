# Data Types

| Type    | Example     | Notes |
|---------|-------------|-------|
| integer | 1, 2, 3     |       |
| float   | 3.14, 1.618 | https://en.wikipedia.org/wiki/IEEE_754 |
| bool    | true, false |       |
| string  | "hello"     |       |

## Declaration

### Declaring Integer

```python
a = 1
```

### Declaring Float

```python
a = 3.14
```

### Boolen 

#### Declaring

```python
a = True
```


### String

Bermula dari table ASCII, berkembang ke Unicode

#### Declaration

```python
name = "Alex"
name = 'Bob'
address = """
Line 1
Line 2
Line 3

"""
address = '''
Line 1
Line 2
Line 3

'''
```

#### Operator

| Operator | Action      |
|----------|-------------|
| +        | Concatenate |
| *        | Multiply    |
| <        | Less Than   |
| >        | Greater     |
| <=       | Less Than or Equal  |
| >=       | Greater Than or Equal |

#### Escape Sequence

| \n | New line       |
|----|----------------|
| \t | Horizontal Tab |

# Operator
- add (+)
- subtract (-)
- multiply (*)
- divide (/)
- floor division (//)
- modulus (%)
- exponentiation (**) -> pangkat
- greater than (>)
- greater than or equal (>=)
- less than (<)
- less than or equal (<=)
- equality (==)


# Casting

Type Conversion

## float to int

```python
a = 3.14
b = int(a)
```

## int to float

```python
a = 1
b = float(a)
```

module use cases:
- day of week (monday, tuesday)
- divisibility -> prime number


definsi:
exponentiation:
	10 pangkat 3 => (10 * 10 * 10)
multiplication:
	10 kali 3   => (10 + 10 + 10)
modulus:
	7 % 2 => 7 dibagi 2, ambil sisasnya
