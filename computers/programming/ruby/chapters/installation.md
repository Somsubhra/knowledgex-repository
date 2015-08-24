Title:   Installation of Ruby
Summary: Installation of Ruby on various platforms
Authors: Somsubhra Bairi

[< Back: Introduction](introduction)

Installation of Ruby
======

[TOC]

### Windows

* Download the Ruby installer for Windows from [here](https://www.ruby-lang.org/en/downloads/).

* Install Ruby using the installer.

* After the installation is complete make sure that the `ruby` executable is on the System Path.


### Linux
Ruby comes pre-installed on many Linux distibutions.

* On Ubuntu and its variants you can install it using the following command:

```
:::bash
sudo apt-get install ruby 
```

* Using yum you can install it by using the following command:

```
:::bash
sudo yum install ruby
```

* You can also download the latest of Ruby [here](https://www.ruby-lang.org/en/downloads/) and follow the installation instructions mentioned in the site.

* You can also install Ruby using `rbenv` or `rvm`.

### OSX

* Ruby can be installed on OSX using `rbenv` or `rvm`.


### IRB (Interactive Ruby)
Ruby comes with an interactive version of shell called IRB. To open it simply enter `irb` into your terminal. 

Enter the following command into `irb` and observer the output:

```
:::ruby
puts 'I am using IRB'
```

[Next: Hello World >](hello-world)