# Data-Types  
## Aim: To study and implement C++ program structure (Data Types)

## Theory:  
This program demonstrates basic input and output operations in C++ by handling different data types, including integers, floating-point numbers, characters, and strings. It begins by prompting the user to input an integer (`d`), a floating-point number (`c`), and a character (`z`), showcasing the use of `cin` for input and `cout` for output. Next, the program asks for the user's name using `cin`, which reads input up to the first whitespace, effectively capturing only the first word if multiple words are entered. The program then outputs the entered name and calculates its length using the `size()` function, demonstrating basic string manipulation.

### Basic (Primitive) Data Types in C++  
Primitive data types in C++ are the most fundamental types that directly represent data. They define the amount of memory allocated for a variable and determine the kind of operations that can be performed on the data.

#### 1. Integer Types  
These types are used to represent whole numbers (positive, negative, or zero).

- **`int`**: The most commonly used integer type, typically occupying 4 bytes in memory, with a range of approximately -2,147,483,648 to 2,147,483,647.  
  - Example: `int number = 42;`

- **`short`**: A smaller integer type, usually 2 bytes, with a range from approximately -32,768 to 32,767.  
  - Example: `short smallNumber = 150;`

- **`long`**: A larger integer type, typically at least 4 bytes, used for wider range values.  
  - Example: `long largeNumber = 100000;`

- **`long long`**: An extended integer type, usually 8 bytes, designed for very large values, with a range of approximately -9 quintillion to 9 quintillion.  
  - Example: `long long veryLargeNumber = 1234567890123;`

#### 2. Floating-Point Types  
These types are used for numbers with fractional parts (decimal numbers). 

- **`float`**: Single-precision floating-point type, generally occupying 4 bytes, suitable for storing decimal numbers with up to 7 significant digits.  
  - Example: `float temperature = 36.6f;`

- **`double`**: Double-precision floating-point type, typically 8 bytes, offering about 15 significant digits of precision.  
  - Example: `double distance = 12345.6789;`

- **`long double`**: Extended-precision floating-point type, often larger than `double` (10, 12, or 16 bytes), used for more precise calculations.  
  - Example: `long double preciseValue = 3.14159265358979323846;`

#### 3. Character Type  
Used to store individual characters, such as letters or symbols.

- **`char`**: Represents a single character, usually occupying 1 byte (8 bits).  
  - Example: `char letter = 'A';`

#### 4. Boolean Type  
Used to store logical values, `true` or `false`.

- **`bool`**: Represents a boolean value, where `true` is 1 and `false` is 0, typically occupying 1 byte.  
  - Example: `bool isRaining = false;`

### Memory Allocation and Size  
The sizes of these data types can vary depending on the system architecture, but typical sizes are:
- `int`: 4 bytes  
- `short`: 2 bytes  
- `long`: 4 bytes (or more)  
- `long long`: 8 bytes  
- `float`: 4 bytes  
- `double`: 8 bytes  
- `long double`: 10, 12, or 16 bytes  
- `char`: 1 byte  
- `bool`: 1 byte  

### Conclusion  
Understanding primitive data types in C++ is essential for effective memory management and optimizing program performance. These data types form the building blocks for more complex data structures.
