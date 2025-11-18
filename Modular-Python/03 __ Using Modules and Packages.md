
---
### Modular Programming with Python

---
03 __ Using Modules and Packages
```
Modules and packages
Packages within packages
Initializing a module
    Initialization functions
Initializing a package
How to import anything
    What does the import statement actually do?
    Using the import statement
    Relative imports
Controlling what gets imported
Circular dependencies
Running modules from the command line
Summary
```

---
*Preface, What this book covers*

Chapter 3, Using Modules and Packages, covers the nuts and bolts of modular
programming using Python, including nested packages, package and module
initialization techniques, relative imports, choosing what gets imported, and how to
deal with circular references.

---
*Summary*

In this chapter, we looked at the details of how Python modules and packages work.
We saw that modules are simply Python source files that get imported using an
import statement, and that packages are directories of Python source files identified
by a package initialization file named `__init__.py`. We learned that packages can
be defined inside other packages to form a tree-like structure of nested packages.
We looked at how modules and packages can be initialized, and how the import
statement can be used in various ways to import modules and packages, and their
contents, into your programs.

We then saw how relative imports can be used to import modules relative to your
current position in the package hierarchy and how the `__all__` variable can be used
to control what gets included in an import.

We then learned about circular dependencies and how to avoid them, and  
we finished by learning about chameleon modules, which can act as both importable
modules and as standalone programs that can be run from the command line.

In the next chapter,  
we will apply what we have learned to the design and implementation  
of a more complicated program, and we will see how a good understanding  
of these techniques will let us build a system that is robust and  
can be updated to meet changing requirements.

---
*Intro*

To be able to use modules and packages within your Python programs,  
you need to understand how they work.  
In this chapter,  
we will examine the nuts and bolts of  
how modules and packages are defined and used in Python.  
In particular, we will:  

_ Review how Python modules and packages are defined  
_ See how packages can be created inside other packages  
_ Discover how modules and packages can be initialized  
_ Learn more about the import process  
_ Explore the notion of relative imports  
_ Learn how to control what gets imported  
_ Find out how to deal with circular dependencies  
_ See how a module can be run directly from the command line,  
and why this can be useful  

