# Introduction

## What is Unix?

Unix is an operating system which was developed in the 1970s and has since
branched into what are known as "Unix-like" operating systems. The two most
widespread Unix-like operating systems are Apple's OS X and Linux. Both of these
operating systems come packaged with a collection of useful tools, many of which
can be used for facilitating data science work. 

## The Unix Philosophy

The first and most important Unix tool you should be aware of is the Unix
philosophy. Books have been written about the Unix philosophy but it boils down
to two basic ideas:

1. Do one thing well.
2. Play well with others.

If you're performing a data analysis where you're writing code you are actually
creating a new piece of software. Your analysis maybe re-purposed in the future
to analyze a new dataset, or a part of your analysis may be excerpted and stuck
into the middle of an unrelated analysis. It is easier to ensure that your
analysis is robust, reproducible, and reusable if the software that you write is
as modular as possible. 

Expanding on the first rule above, an analysis or a
piece of software is easier to use, debug, and understand if it only has one
purpose with a limited number of inputs and outputs. Modularizing software or
an analysis this way is also useful because individual modules can be strung
together to form more complex analyses. If there's a problem with one
compartmentalized module in a series of analyses it's easier to isolate and
address one broken or misused module than to wade through something
monolithic and opaque.

The second rule speaks to the usability of the analysis or the software that
you produce. Try to be compassionate toward other human beings when documenting 
and commenting your code, whether they be colleagues or a future version of 
yourself. If your program might produce errors try to write error messages that
would make sense to a new user, so the user can quickly correct the problem. 
When it comes to your code interacting with other programs, make sure that the 
input and output data types are at least parsable, and at best standardized and
common. Think `csv`, `tsv`, `json`, or some other well structured data format.

## The Shell

Throughout this book you will be interacting with a computer program called the
shell. The shell is an interpreter, which means that it's a computer program
that reads and then executes one line of code at a time. There are several 
popular shell programs but this book uses the Bash shell, which is the
default shell on Mac OS X and Linux. The shell is not a suitable environment to
do all of your data science work, however it provides a simple yet powerful 
interface for manipulating computers and interacting with data.

## Notes Before Starting

This book is meant to be used with a computer where you have full administrative
privileges. If you're using this book with a computer that you own this 
shouldn't be a problem, however if you are using a computer at work or school 
you may need to contact a systems administrator in order to install and use
the tools discussed in the following chapters.
