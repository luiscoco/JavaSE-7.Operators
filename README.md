# JavaSE-7.Operators

See the Udemy course: https://www.udemy.com/course/curso-certificacion-profesional-desarrollador-java-se-11

Java operators are symbols that perform operations on variables and values. Here are some common Java operators with examples:

Arithmetic Operators:

```+``` (Addition)

```-``` (Subtraction)

```*``` (Multiplication)

```/``` (Division)

```%``` (Modulus)

```java
int a = 10, b = 3;
int sum = a + b;      // 13
int difference = a - b; // 7
int product = a * b;   // 30
int quotient = a / b;  // 3
int remainder = a % b; // 1
```

Relational Operators:

```==``` (Equal to)
```!=``` (Not equal to)
```>``` (Greater than)
```<``` (Less than)
```>=``` (Greater than or equal to)
```<=``` (Less than or equal to)

```java
int x = 5, y = 8;
boolean isEqual = x == y;       // false
boolean notEqual = x != y;      // true
boolean greaterThan = x > y;    // false
boolean lessThan = x < y;       // true
boolean greaterOrEqual = x >= y; // false
boolean lessOrEqual = x <= y;    // true
```

Logical Operators:

```&&``` (Logical AND)
```||``` (Logical OR)
```!``` (Logical NOT)

```java
boolean condition1 = true, condition2 = false;
boolean andResult = condition1 && condition2; // false
boolean orResult = condition1 || condition2;  // true
boolean notResult = !condition1;               // false
```

Increment and Decrement Operators:

```++``` (Increment)
```--``` (Decrement)

```java
int count = 5;
count++; // Increment by 1, count is now 6
count--; // Decrement by 1, count is now 5 again
```

Assignment Operators:

```=``` (Assignment)
```+=```, ```-=```, ```*=```, ```/=```, ```%=``` (Compound Assignment)

```java
int num = 10;
num += 5; // Equivalent to num = num + 5, num is now 15
```

