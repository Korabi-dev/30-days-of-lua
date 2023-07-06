# Day 2 | Data types and Variables

Lua let's us store data in what we call "variables", think of a variable as a bucket, and what we put in the bucket as the data.

## Variables

**Example**

```lua
local customer = "Korabi"
```

Okay, let's break this down using our bucket analogy from earlier. Here the word "`local`" is used to tell lua that we are about to define a variable locally (you dont need to know what that is just yet), "`customer`" is the bucket, and "`Korabi`" is a piece of paper we put inside the bucket, now in the same way the bucket holds the piece of paper with "Korabi" written on it, the variable called "`customer`" holds the string "Korabi" in it also.

## Data Types

**Example**

```lua
local myString = "Hello, World!"
local myNumber = 69
local myBoolean = true
local myTable = {"Tom", "Jerry"}
```

### Strings

Strings are bits of text that can represent anything, it can be a single character, a full sentence, or just random letters and numbers. String are sorrounded by quotes ("").

### Numbers

The name is self explanatory, numbers in lua can hold any number between `-2⁶³` up to `2⁶³`.

### Booleans
In lua booleans hold only 2 values, either `true` or `false`, this is the basis for all logical operators such as: if this is true, then do this

### Tables
Tables in lua are basically a list that can hold any data type inside of itself for later reference, such as Strings, Numbers, Booleans, and other Tables. They start with a `{` and end with a `}`, and elements inside of them must be separated by either a comma or a semicolon. Each element will have its own "index" in the table which is the number that keeps track where that specific value is.