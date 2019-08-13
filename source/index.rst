Welcome to the Docs
===================
``preamble``
Here lies the documentation for the programming language jewl

Basic Syntax
============

print
-----


This is how you print to the console

Print only prints the text, no newline characters

The syntax is as follows::

   print "text ";
   print "more text";

   output:
   text more text

println
-------

This does the the same as print but adds a newline character at the end

The syntax is as follows::

   println "text";
   println "more text";

   output:
   text
   more text

Integers
--------
print and println can both print integers (but not in strings currently)
That syntax is as follows::

   println 1;
   print 1;
   output:
   1
   1

Expressions
-----------
You can also print expressions

That syntax is as follows::

   println 1+1;
   print 1*2;
   output:
   2
   2

Currently Addition, Subtraction, Multiplication, and Division are supported up to Double whole integers (eg: 0-99)

If Statements
-------------
Jewl also supports If Statements

Their syntax being::

   if(num1+num2==num3) {
       code
   }

Theoretically any type of Jewl code could be in the if statement but I have only tested printing

Variables
---------
Variables are also supported

Their Syntax being::
   //For Integers
   Int varname=0;
   //For Strings
   Str varname="test";

The syntax for printing variables is::

   println ${varname};

