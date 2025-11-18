
---
### Modular Programming with Python

---
07 __ Advanced Module Techniques
```
Optional imports
Local imports
Tweaking imports using sys.path
Import gotchas
    Using an existing name for your module or package
    Naming a Python script after a module or package
    Adding package directories to sys.path
    Executing and importing the same module
Using modules and packages with the Python interactive interpreter
Dealing with global variables
Package configuration
Package data
Summary
```

---
*Preface, What this book covers*

Chapter 7, Advanced Module Techniques, looks at some of the more distinctive
aspects of modular programming in Python, including optional and local imports,
tweaking the module search path, "gotchas" to be aware of, how to use modules and
packages for rapid application development, working with package globals, package
configuration, and package data files.

---
*Summary*

In this chapter,  
we looked at a number of the more advanced aspects  
of working with modules and packages in Python.  
We saw how a `try..except` statement can be used to implement optional imports,  
and how an import statement can be placed inside a function  
so that the module only gets imported when that function is executed.  
We then learned about the module search path and  
how you can modify `sys.path` to change the way  
the Python interpreter looks for modules and packages.  

We then looked at some of the gotchas related to the use of modules and packages.  
We learned about name masking, where you define a module or package  
with the same name as a module or package in the Python Standard Library,  
which can lead to unexpected failures.  
We looked at how giving a Python script the same name  
as a Standard Library module can also cause name masking problems,  
and how adding a package directory or sub-directory to `sys.path`  
can cause a module to be loaded twice,  
leading to subtle problems with global variables within that module.  
We saw how executing a module and then importing it also leads  
to that module being loaded twice, which can again lead to problems.  

We next looked at how you can use the Python interactive interpreter  
as a type of rapid application development (RAD) tool  
to quickly find and fix problems within your modules and packages, and  
how the `importib.reload()` command allows you to reload a module  
after you have changed the underlying source code.  

We finished our survey of advanced module techniques  
by learning how to define global variables  
that are used throughout a package, how to handle package configuration, and  
how to store and access data files within a package.  

In the next chapter,  
we will look at some of the ways  
in which you can test, deploy, and share  
your Python modules and packages.  

