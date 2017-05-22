# Numbers and Mathematics

## An Overview of Ruby Numbers

In most programming languages, number is a fundamental type of the data. You can open `irb` (interactive Ruby) and try few lines to play around with Ruby numbers :

```
$ irb
:001 > 3
=> 3
:002 > 2 + 7
=> 9
:003 > 3.0 / 2
=> 1.5
```

Because numbers in Ruby are objects, you can call the method of the number using the **dot** directly, for example:

```
:004 > (4.3).ceil
=> 5
:005 > (2.7).floor
=> 2
:006 > (1.8).round
=> 2
```

You can even "ask" the number whether it is an odd or an even number:

```
:007 > 7.odd?
=> true
:008 > 7.even?
=> false
```

You can use the `class` method to print out the class which the number belongs to:

```
:009 > 5.class
=> Integer
:010 > (3.1).class
=> Float
```

From the example `irb` presented above, for now, you can view it as `number 5 is a kind of Integer` and `number 3.1 is a kind of Float`. In the later section, you will see there are more other kinds of number types.

## Arithmatic Expressions

(Continued ...)

## Common Used Methods

(Continued ...)

## Numeric Class Hierarchy

(Continued ...)
