# Collection of notes in the C language

**Scratch:   Say (Hello, world)**

```C
printF("hello, world\n");
```

* All printed words are called strings, and all strings are enclosed by "string" <br>
* The \n tells computer to start a new line <br>
* The ; is like the period of a sentence and tells the computer that this is the end of the statement

**Scratch:  Set counter to 0**

```C
int counter = 0;
```

* In C, you must declare the type of variable you are creating <br>

**Scratch:  Change counter by 1**

```C
counter = counter + 1;
counter += 1; 
counter++;
```

* The = sign is not "equals", but rather assign
* Once the variable is created, you do not need to repeat what type of variable it is

**Scratch:  If x < y then say "X is less than Y"**

```C
if (x<y)
{
printf("X is less than Y\n");
}
```

**Scratch:  If x < y then say "X is less than Y", else say "X is not less than Y"**

```C
if (x<y)
{
printf("X is less than Y\n");
}
else
{
printf("X is not less than Y\n");
}
```
