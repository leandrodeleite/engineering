
---
### Modular Programming with Python

```
Reviews
  skeptic
  Mike Driscoll
  CynA
```


---
*Reviews*
| *skeptic*
| 5.0 out of 5 stars  
| Reviewed in the United States on November 6, 2017

Great book on a very important topic.  
Highly recommended  

Python is complex language with even more complex environment and  
its module system is the critical part of it.  
For example  
Python standard library is structured as a collection of modules.  
The author gives you an excellent overview of Python module system,  
gives important recommendation about creation of your own modules  
(and provide several examples, including generator example in chapter 4),  
as well as warns about gotchas.  
Interplay between modules and namespaces covered in Chapter 7  
is alone worth several times of the price of the book.  
For example few understand that the import statement  
adds the imported module or package to the current namespace,  
which may or may not be the global namespace.  
The author also covers the problem of "name masking" in this chapter.  

Ability to write a large script using your own modules  
is a very important skill that few books teach.  
Usually intro books on Python try to throw everything that language contains  
into the sink, creating problems for whose who study the language,  
even in cases when they already knew some other programming languages  
such as C++ or Perl.  
Ability not to cover some features of the language  
usually are complete absent in authors of such books.  

Most of the authors of Python books talks a lot about how great Python is,  
but never explain why.  
This book explains probably the most important feature  
of this scripting language which makes is great  
(actually inhered from Modula 3).  
Also most intro books suffer from excessive fascination with OO  
(thanks God this fad is past its peak).  
This book does not.  

Publishing of books that are devoted to important topics has great value as:  
you have nowhere to go to get information that it provides.  
But it is very risky business.  
Of cause if you are diligent you can collect this information  
by reading a dozen of book by extracting and organizing  
into some presentation relevant parts.  
But this is the work better reserved for personalities  
which corresponds to famous Sherlock Holms and  
it presuppose that you have pretty of time to do it.  
Usually meeting both of those two conditions is pretty unrealistic.  

So it takes a certain about of courage  
to write a book devoted to a single specific feature of Python and  
the author should be commended for that.  

That's why I highly recommend this book  
for anybody who is trying to learn the language.  
It really allow you to understand a single  
the most critical feature of the Python language.  

The book contain 9 chapters.  
Here are the titles of those chapters:  

1 __ Introducing Modular Programming  
2 __ Writing Your First Modular Program  
3 __ Using Modules and Packages  
4 __ Using Modules for Real-World Programming  
5 __ Working with Module Patterns  
6 __ Creating Reusable Modules  
7 __ Advanced Module Techniques  
8 __ Testing and Deploying Modules  
9 __ Modular Programming as a Foundation for Good Programming Technique  


NOTE:  
In chapter 8 the author covers unrelated but an important topic  
about how to prepare your modules to publication and upload them to GitHub.  
Using GitHub became now very popular among Python programmers and  
the earlier you learn about this possibility the better.  

Chapter 8 also covers important topic about installation of Python packages.  
But unfortunately the coverage is way to brief and  
does not cover gotchas that you might experience installing such packages as Numpy.  

I would like to stress it again:  
currently the book has no competition in the level of coverage of this,  
probably the most important feature of Python language.  


---
*Reviews*
| *Mike Driscoll*
| 4.0 out of 5 stars
| Reviewed in the United States on June 17, 2016

A Great Intro to Modular Programming


Earlier this year or late 2015,  
Packt Publishing asked me to be technical reviewer  
for a book called “Modular Programming with Python” by Erik Westra.  
It sounded really interesting and  
it ended up being one of the best books I’ve read from Packt.  
Note that I am the sole technical reviewer of the book.  

Modular Programming with Python is actually quite fun to read.  
It is designed to help you learn how to make your code more modular and  
gives some really good examples.  
The first chapter begins by going over the way  
Python itself organizes its modules and packages.  
It goes on to explain why modular programming can be important and  
it has a neat example of creating your very own module,  
which happens to be a caching module.  

The second chapter is all about creating your first modular program.  
It takes you through the steps you might go through  
to design a program in a modular fashion and then actually implements it.  
During the design phase, the author just stubs out the interface.  
Then in the implementation phase we get to actually add the code.  

For chapter three, we learn how modules and packages are initialized.  
The author also goes over Python’s importing system.  
We learn how imports work, what relative imports are,  
controlling what gets imported, circular imports and more.  

Chapter four is about creating a modular charting package.  
We learn how to chart using the pillow package,  
which is a fork of the Python Imaging Library (PIL).  
Then the author talks about how requirements for a projects change and  
how we must respond to them.  
In this example,  
we need a way to do vector images which pillow doesn’t support.  
So the author shows how to add the ability to create charts  
using Reportlab or pillow.  
This is also a really great chapter.  

Chapter five looks at modular patterns, like encapsulation, wrappers, etc.  
I think the part I found most interesting  
was the portion of the chapter that covered dynamic imports, plugins and hooks.  

In Chapter six, we learn about reusable modules.  
The author first describes what a reusable module is and  
then gives some examples.  
The rest of the chapter is devoted to creating a reusable module  
which happens to be a unit conversion module.  

Chapter seven digs even more into Python’s importing system.  
It covers such items as optional imports, local imports,  
adding packages to `sys.path`, various import “gotchas”,  
dealing with globals and more.  
This was actually one of my favorite chapters.  

For chapter eight, we get a change of pace.  
It’s all about testing our modules and deploying them.  
The chapter only gives the basics on unit tests,  
code coverage and test driven development.  
The bulk of the chapter is about getting a module ready  
for publication to Github or the Python Package Index.  

The final chapter is supposed to demonstrate  
how modular programming techniques can make  
the process of programming itself more effective.  
It gives a pretty short example and wraps up the book.  

Overall I found this book conveyed its message very well.  
The code examples are straight-forward and easy to understand.  
The writing is very good.  
Much better than what I normally see in Packt publications.  
I love reading neat or just interesting code and this book has several great examples.  
I did feel like the book ended a bit abruptly.  
While I don’t know what should have been added,  
I just felt like it could have had another chapter or two.  
Regardless,  
I do recommend this book to anyone who is having trouble organizing their code.  


---
*Reviews*
| *CynA*
| 3.0 out of 5 stars
| Reviewed in the United States on December 26, 2016

Great book.

This is a great book  
for understanding how to organize your python applications.  

The only thing I didn't like was  
the author was hell bent on not using classes at all.  

Like there was an example where using class would have made the examples easier  
but the author used all functions with globals and locals.  
It was weird.  

While I understand that  
the author probably did that so it would be easier for beginners?  
But then again when you are buying a book about  
how to program organize your code modularly,  
chances are you already know what a class is.  

I just seriously don't understand  
the forced avoidance with classes in the examples.  
Other than that the book is great.  

