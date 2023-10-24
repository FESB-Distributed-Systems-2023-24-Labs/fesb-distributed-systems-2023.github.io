# Coding Convention

## Table of Contents

## What is Coding Convention
Coding Convention is a set of rules that states how the code should be written. The idea behind a coding convention is to make the code:

1.  Readeble
2.  Uniform (multiple people will write code in the same fashion)

Readable code helps developers avoid hard-to-find bugs and saves development time, as well as sanity.
Uniform code helps other parties (new members) to read code faster and get the intention behind the code.

## General Guidelines
1. Prefer simple code that states intention rather than instruction
2. Prefer slower but more simpler and readable code, optimize only when necessary
> "Premature optimization is the root of all evil"
> 
> ~ Donald Knuth in his *Structured Programming With Go To Statements* paper

## Rules
### Naming Rules

- **MUST** and **MUST NOT/NEVER** - Must always be obeyed, no exceptions
- **SHOULD** - Try to obey as much as possible, but exceptions are allowed
- **CAN/COULD** - Try **not** to use too much, but it is not prohibited

#### Classes and Structs

- All classes and structs **MUST** use [*pascal case*](https://www.pluralsight.com/blog/software-development/programming-naming-conventions-explained#pascal-case)
- Class and struct names **MUST** contain only letters of the english alphabet [A-Z and a-z]
- Class and struct names **CAN** contain underscores "_" and numbers [0-9]

```diff
+ GOOD:
```
```csharp
class Program
{
   /* ... */
}

struct Image
{
   /* ... */
}

class BankingAccount
{
   /* ... */
}
```

```diff
- WRONG:
```
```csharp
class program
{
   /* ... */
}

struct _image
{
   /* ... */
}


class Banking_Account
{
   /* ... */
}
```

#### Methods
- Methods **MUST** be `private` unless they are accessed outside the class, then they must be `public` ([Encapsulation](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming)))
- All methods **MUST** use [*pascal case*](https://www.pluralsight.com/blog/software-development/programming-naming-conventions-explained#pascal-case)
- methods names **MUST** contain only letters of the english alphabet [A-Z and a-z]
- methods names **CAN** contain underscores "_" and numbers [0-9]

```diff
+ GOOD:
```
```csharp

```

```diff
- WRONG:
```
```csharp
class program
{
   /* ... */
}

struct _image
{
   /* ... */
}


class Banking_Account
{
   /* ... */
}
```