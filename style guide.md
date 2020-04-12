# Style guide

## Table of contents
* Generic
* SQL
* Javascript
* C#
* Java

---



# Gereric
## Abreviations
#### Good
Only use very common abreviations for example:
| abreviation | name |
|-|-|
|img | image |
| ex | exception |

abreviations for local variable is also ok for example:
```C#
Stringbuilder sb = new Stringbuilder();
```

#### Bad
```C#
private UserAuthorizationRepository uar;
```

---


## If statements 
The curly braces should start inf the same line as the if statement.
Code may bot be on the same line as the if statement.
The if statement has to end on a new line. Al following else and else if statements should follow the same principle and start one line under the ending of the if statement.

Shorthand if statements are allowed, for short code that is not likeley to change.



#### Good
```Java
if(){
    myFunction();
}
else{
    myOtherFunction();
}

// Also good, if short and not likely to change

if()
    myFunction();
else
    myOtherFunction();

```

#### Bad 
```Java
if(/* condition */)
{
    /* Code */
} else 
{
    /* Code */
}

// Also bad

if(/* condition */) myFunction();


```