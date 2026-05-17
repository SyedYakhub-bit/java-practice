# Java Practice

Java practice exercises — not a framework, not a library. A working record of core Java concepts learned hands-on.

---

## What's Inside

### OOP
| File | What it covers |
|------|---------------|
| `AccessModifiers.java` | Public/private access with a vowel-counting class |
| `MethodOverloading.java` | Same method name, different parameters |
| `MethodOverriding.java` | Subclass overriding a parent method |
| `OverloadingExample.java` | Further overloading practice |
| `OopsPractice.java` | Class design with fields, constructors, display methods |
| `Circle.java` | Object instantiation and method calls |
| `Practice/Pen.java` | Class and object basics |
| `CentralTraffic.java` / `IndianTraffic.java` | Inheritance example via traffic system |

### Strings
| File | What it covers |
|------|---------------|
| `StringDuplicate.java` | Find duplicate characters in a string |
| `StringReverse.java` | Reverse a string using a loop |
| `ReverseString.java` | Alternate reverse approach |
| `StringEqual.java` | `equals()` vs `==` comparison |
| `TrimString.java` | `trim()` and whitespace handling |
| `Palindrome.java` | Check if a string is a palindrome |
| `Practice/StringPalindrome.java` | Palindrome using `StringBuilder` |
| `Practice/UpperCaseToLowerCase.java` | Case conversion methods |

### Loops & Conditionals
| File | What it covers |
|------|---------------|
| `Loops.java` | `for`, `while` loop patterns |
| `DoWhile.java` | `do-while` loop |
| `Switch.java` | `switch` statement |
| `EvenOdd.java` | Even/odd check with `if-else` |
| `OddNum.java` | Print odd numbers in a range |
| `SumEven.java` | Sum even numbers in a range |
| `LeapYear.java` | Leap year logic with nested conditionals |

### Arrays
| File | What it covers |
|------|---------------|
| `ArraySearch.java` | Linear search in an array |
| `MaxMin.java` | Find max and min in an array |
| `DuplicateCount.java` | Count duplicate elements |
| `Practice/ArraySum.java` | Sum all elements in an array |
| `Practice/MaxMinElementArray.java` | Max/min with cleaner approach |

### Programs
| File | What it covers |
|------|---------------|
| `HelloJava.java` | First program |
| `CalculateSum.java` | Sum of two numbers |
| `SumOfDigits.java` | Extract and sum digits of a number |
| `PrimeNumber.java` | Prime number check |
| `GuessNumber.java` | Number guessing game with `Random` and `Scanner` |
| `SwapNumbers.java` | Swap two values (with and without temp variable) |
| `GreaterNum.java` | Find the greater of two numbers |
| `AreaRectangle.java` | Rectangle area calculation |
| `CircleArea.java` | Circle area using `Math.PI` |
| `TemperatureConv.java` | Celsius to Fahrenheit conversion |
| `SimpleCalci.java` | Basic calculator with `switch` |
| `RectanglePattern.java` | Print a rectangle using nested loops |
| `Functions.java` | Method definitions and calls |
| `ReimbursementCalculator.java` | Multi-person expense split with `ArrayList` |

### Exception Handling
| File | What it covers |
|------|---------------|
| `DivisionZeroException.java` | Catch `ArithmeticException` on divide-by-zero |
| `MultipleExceptions.java` | Multiple `catch` blocks |
| `EvenNumberException.java` | Custom exception class |
| `Assessment.java` | `try-catch` with `NullPointerException` |

### Testing Experiments
| File | What it covers |
|------|---------------|
| `API_Testing.java` | REST API call using RestAssured |
| `APITestingMessage.java` | RestAssured response handling |
| `SampleSelenium.java` | Selenium placeholder |

---

## How to Run

Any file compiles and runs the same way:

```bash
# From the src/ directory
javac FileName.java
java FileName
```

Example:
```bash
cd src
javac GuessNumber.java
java GuessNumber
```

For files in the `Practice/` subdirectory:
```bash
cd src
javac Practice/FileName.java
java Practice.FileName
```

> Requires Java 8 or later. No build tools needed for the core exercises.

---

## Concepts Covered

- Classes, objects, constructors, and instance methods
- Inheritance and method overriding
- Method overloading (compile-time polymorphism)
- Access modifiers (`public`, `private`, `protected`)
- `String` methods: `equals()`, `trim()`, `charAt()`, `toLowerCase()`, `StringBuilder`
- Control flow: `if-else`, `switch`, `for`, `while`, `do-while`
- Arrays: traversal, search, min/max, duplicate detection
- `Scanner` for user input, `Random` for number generation
- `ArrayList` and basic `List` usage
- Exception handling: `try-catch-finally`, multiple exceptions, custom exceptions
- Basic math with `Math` class

---

## Why This Exists

Personal learning repo — built while preparing Java fundamentals for QA and developer interviews.