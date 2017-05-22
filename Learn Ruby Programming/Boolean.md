# Boolean

## Overview of Boolean Values in Ruby

Although we have `Number`, `String` and even `Symbol` to help us represent different kinds of data. We still have another issue to consider whether the data is either yes or no, true or false etc. This kind of data describes the truth values of the logic is usually called [**Boolean values**](https://en.wikipedia.org/wiki/Boolean_data_type).

Same as most of the programming language, Ruby represent Boolean value as `true` or `false` :

```ruby
true.class   # TrueClass
false.class  # FalseClass
```

They represents different class, which are the `TrueClass` and the `FalseClass`. We shall see how Boolean kind of values work in Ruby. 

## Question Methods

Usually, when calling a method which ends with the `?` mark, it returns only `true` or `false` as if you were asking the state or the conditions of the object. For example, to ask whether the string starts/ends with a piece of smaller string pattern, we can use `String#start_with?` or `String#end_with?` method:

```ruby
"Hello World".start_with?("World") # => false
"Hello World".end_with?("World")   # => true
```

To ask whether a number is between another two numbers, we can use the `Integer#between?` method. It should specify two numbers which represents the starting and the ending range, for example:

```ruby
5.between?(0, 10) # => true
5.between?(6, 10) # => false

# The range specified in between? method is inclusive
5.between?(5, 10) # => true
5.between?(0, 5)  # => true

5.between?(10, 0) # => false   It cannot work in descending order
```

(However, if you change range into descending order, it can not evaluate correctly.)

That's enough for the examples, you can see any method ends with a question mark returns either `true` or `false` value.

## Logical Expressions

### Comparison Operators

The logical expression can describe the truth state of combination of multiple events, such as the statements below for example:

```
The statement : "3 is larger than 1", is "true"
The statement : "10 is small than 6", is "false"
```

In Ruby, we can use **comparison operator** to describe the logical expression, for instance according to the statements above:

```ruby
puts "The expression '3 > 1' is #{3 > 1}"
# The expression '3 > 1' is true
puts "The expression '10 < 6' is #{10 < 6}"
# The expression '10 < 6' is false
```

There are some common operators in Ruby which stand the role of comparison:

(Continue ...)

### Logical Operators

(Continue ...)
