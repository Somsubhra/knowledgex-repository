Title:   Ruby basics
Summary: Basics of Ruby
Authors: Somsubhra Bairi

[< Back: Hello World](hello-world)

Ruby Basics
=======

[TOC]

### Identifiers
Identifiers are the names of constants, variables or methods.

In Ruby, identifiers are case sensitive. For example: `myVar` and `myvar` are interpreted differently.

In Ruby, alphanumeric characters and the underscore character `_` are allowed in naming of identifiers.

### Reserved Keywords

Here is a list of keywords reserved in Ruby.

| | | | |
| --- | --- | --- | --- |
| `BEGIN` | `do` | `next` | `then` |
| `END` | `else` | `nil` | `true` |
| `alias` | `elsif` | `not` | `undef` |
| `and` | `end` | `or` | `unless` |
| `begin` | `ensure` | `redo` | `until` |
| `break` | `false` | `rescue` | `when` |
| `case`| `for` | `retry` | `while` |
| `class` | `if` | `return` | `while` |
| `def` | `in` | `self` | `__FILE__` |
| `defined?` | `module` | `super` | `__LINE__` |

They cannot be used as variable or constant names. They can however be used as method names.

### BEGIN statement
The `BEGIN` block contains code to be executed before the rest of the script.

For example:

```
:::ruby
#!/usr/bin/ruby

puts 'Main script body running'

BEGIN {
    puts 'Initializing script'
}
```

This will result in the following output:

```
Initializing script
Main script body running
```


### END statement
Similar to `BEGIN`, the `END` block contains code to be executed before the end of the script.

Continuing with the previous example, we add an `END` block to it.

```
:::ruby
#!/usr/bin/ruby

puts 'Main script body running'

END {
    puts 'Script exiting'
}

BEGIN {
    puts 'Initializing script'
}
```

This will result in the following output:

```
Initializing script
Main script body running
Script exiting
```

### Comments
Comments are parts of code which are not interpreted by the interpreter.

A piece of text is made a comment by adding a `#` before it.

For example
```
:::ruby
#!/usr/bin/ruby

# This is a one line comment
puts 'Hello World!'
```

Multiline comments can be made by adding the `=begin` and `=end` at the starting and ending lines respectively.

For example
```
:::ruby
#!/usr/bin/ruby

=begin
This is the an
example of
multiline comment.
=end

puts 'Hello World!'
```

[Next: ]()