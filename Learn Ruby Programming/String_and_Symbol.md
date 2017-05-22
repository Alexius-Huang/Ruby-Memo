# String and Symbol

## An Overview of Ruby String and Symbol

Strings are widely used in Ruby programming language, it can be represented as a series of characters and nested by double or single quotes.

```ruby
"This is a string nested by double quotes"
'This is another string nested by single quotes'
```

You can directly call the method on `String` object:

```ruby
"maxwell".capitalize # => "Maxwell"
"maxwell".length     # => 7
```

And of course, the class of the string is `String`:

```ruby
"This is a string".class # => String
```

Symbol is another special type in Ruby language, symbol data started with a colon:

```ruby
:this_is_a_symbol
:"This is also a symbol but rarely used"
```

You can call the symbol object with some methods :

```ruby
:maxwell.capitalize # => "Maxwell"
:maxwell.length     # => 7
```

The class of symbol type data is `Symbol`:

```ruby
:maxwell.class # => Symbol
```

Let's move on and explore more on `String` and `Symbol` type data, it might be confused at first, but there are some reasons to use both two kinds of data type in practice.

## Data Type Conversion

### String v.s. Symbol
(Continue ...)

### String v.s. Number
(Continue ...)

## Difference Between String and Symbol
(Continue ...)