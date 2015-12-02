## Introduction

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

- the measure of a data scientist: can you effectively interact with data?
- to interact you need to use a computer
- Unix and Unix-like systems provide a good way to interact
- can be intimidating at first but the purpose of this book is to get you up over the learning curve
- the shell is not a suitable environment to do all of your data science