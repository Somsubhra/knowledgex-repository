Title:   Installation of Ruby
Summary: Installation of Ruby on various platforms
Authors: Somsubhra Bairi

[< Back: Installation](installation)

Hello World!
======

Ruby files have the extension `.rb`. Put the following code in a file called `hello_world.rb` (or a name of your choice):

```
:::ruby
#!/usr/bin/ruby
puts "Hello World!";
```

The first line is a shebang which mentions the interpreter of the script which is the ruby interpreter here.

To run the script open the terminal in the directory of the file `hello_world.rb` and issue the following command to invoke the Ruby interpreter.

```
:::bash
$ ruby hello_world.rb
```

The Ruby interpreter interprets the ruby script and outputs the following:

```
Hello World!
```

So that is it, plain and simple, your first script written in Ruby.

[Next: Ruby basics >](basics)