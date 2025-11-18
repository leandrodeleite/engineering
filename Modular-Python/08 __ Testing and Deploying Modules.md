
---
### Modular Programming with Python

---
08 __ Testing and Deploying Modules
```
Testing modules and packages
    Testing with the unittest Standard Library module
    Designing your unit tests
    Code coverage
    Test-driven development
    Mocking
    Writing unit tests for your modules and packages
Preparing a module or package for publication
Uploading your work to GitHub
Submitting to the Python Package Index
Using pip to download and install modules and packages
Summary
```

---
*Preface, What this book covers*

Chapter 8, Testing and Deploying Modules, examines the concept of unit testing, how
to prepare your modules and packages for publication, how to upload and publish
your work, and how to make use of modules and packages written by other people.

---
*Summary*

In this chapter,  
we learned about the various ways  
in which you can test your Python modules and packages.  
We learned about unit testing and how the `unittest` package  
in the Python Standard Library makes it easier  
to write and use unit tests for the modules and packages that you develop.  
We saw how unit tests use the assert statement  
(or the various `assertXXX()` methods  
if you are using the `unittest.TestCase` class)  
to raise an `AssertionError` if a particular condition has not been met.  
By writing various unit tests,  
you can ensure that your modules and packages are working  
the way you expect them to.  

We then looked at the process of preparing a module or package for publication, and  
saw how GitHub provides an excellent repository  
for storing and managing the source code for your modules and packages.  

After creating our own test package,  
we worked through the process of submitting this package to the Python Package Index.  
Finally, we learned how to use `pip`, the Python Package Manager,  
to install a package from PyPI into your system's site-packages directory,  
before looking at the ways in which a requirements file or  
a virtual environment can be used to help manage your program's dependencies.  

In the final chapter of this book,  
we will see how modular programming acts more generally  
as the foundation for good programming techniques.  

---
*Intro*

In this chapter,  
we will delve further into the concept of sharing modules.  
Before you can share a module or package,  
you need to test it to ensure that it is working properly.  
You also need to prepare your code and know how to deploy it.  
To learn these things, we will cover the following topics:  

- See how unit tests can be used to ensure  
that your module or package is working properly  
- Learn how to prepare a module or package for publication  
- Find out how GitHub can be used to share your code with others  
- Examine the steps involved in submitting your code  
to the Python Package Index  
- Discover how to use pip to install and use packages written by other people  

