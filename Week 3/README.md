# Operators, Strings and Control Flows

### Objective
To learn: 
- The different types of operators in Python: Arithmetic operators, comparison operators, logical operators, identity operators, assignment operators, membership operators, and Bitwise operators.
- The string format structures in Python: modifying strings, splitting strings, and string formatting.
- The control flow structures in Python: If statements, loops, and conditional statements.

### Tools Used: 
- Google Colab

### Step-by-step Process

### Operators 

Operators are used to perform computing actions on values and variables. They are:

- Arithmetic Operators: They are used to perform arithmetic calculations on values.
    * (addition), - (subtraction),
    * (multiplication),
    * / (division),
    * //(floor division),
    * %(modulo, remainder),
    * ** (exponential/ power).
      
![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operators%20-%20Ari%20(%2B%2C%20_%2C%20).png)
![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20Ari%202.png)

- Comparison operators: compare two variables to return a boolean 
    * (>) (greater than)
    * < (Less than)
    * == (equal to)
    * (>=) (greater than or equal to)
    * <= (less than or equal to)
    * != (not equal to)

![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20comp%201.png)
![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20comp%202.png)

- Logical Operators
  * "and" - evaluates two conditions and returns a boolean (True or False). When true, both conditions are correct.
  * "or" - returns true when one of the conditions is correct.
  * "not" - negation. Returns true when the variable is not found in the command.
 
![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20log.png)

- Assignment operators - used to assign variables
  * = assigns variable
  * += add value to a variable
  * -= subtracts value from variable
  * /= divides variable by the value
  * *= multiplies variable by the value
  * It applies to all the arithmetic operators.

![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20Assign.png)

- Bitwise operators: it is used to manipulate integers into binary bits (0s and 1s). Each operator has a bitwise rule. 
  * & (ampersand) - also called bitwise "and".
    * Only bits of 1 and 1 can give 1; any other value gives 0.
  * | (pipe) - also called bitwise "or"
    * Only 0 and 0 bits will not give 1; any other number gives 1, e.g., 0 and 1 = 1
  * ^ (caret symbol) - also called bitwise "xor"
    * gives 1 if bits differ and 0 if bits are the same. 
  * (>>) (right shift operator) - each shift divides (floor division) by the n position, e.g., x >> 2. X will divide each         outcome by two for two times.
  * (<<) (left shift operator) - each shift multiplies by n positions. e.f x << 3 each outcome is multiplied 3 times.
  * (~) (tilder) - gives a negation output on integers using two's complement.
    * It is also called the bitwise (not)

![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20bit%201.png)
![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20bit%202.png)

- Membership operators: checks the existence of a value/item in a sequence or collection.
  * "in" - checks if an item exists in a sequence and returns a boolean.
  * "not in" - check if an item is not in a sequence and returns a boolean

![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20member.png)

- Identify Operators: checks if two objects are the same in memory, not just in values.
  * "is"
  *  "is not"

![](https://github.com/sopy-anne/Data-Science-and-Machine-Learning-Lab---Weekly-Practice/blob/main/Week%203/Operator%20-%20Ident.png)
