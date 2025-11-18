
---
### Modular Programming with Python

---
05 __ Working with Module Patterns
```
Divide and conquer
Abstraction
Encapsulation
Wrappers
Extensible modules
    Dynamic imports
    Plugins
    Hooks
Summary
```

---
*Preface, What this book covers*

Chapter 5, Working with Module Patterns, looks at a number of standard patterns for
working with modules and packages, including the divide and conquer technique,
abstraction, encapsulation, wrappers, and how to write extensible modules using
dynamic imports, plugins, and hooks.

---
*Summary*

In this chapter,  
we saw that the ways in which modules and packages are used  
tend to follow standard patterns.  
We examined the divide-and-conquer pattern,  
which is the process of breaking a problem down into smaller parts, and  
saw how this technique both helps to structure your programs and  
clarify your thinking about the problem you are trying to solve.  

We next looked at the abstraction pattern,  
which is the process of hiding complexity  
by separating what you want to do from how to do it.  
We then examined the notion of encapsulation,  
which is where you store data about something  
but hide the details of how that data is represented  
from the rest of the system, and  
use getter and setter functions to provide access to that data.  

We then turned to the concept of wrappers, and  
saw how wrappers can be used to simplify  
the interface to a complex or confusing API,  
to convert data formats, to implement cross-language compatibility, and  
to add testing and error-checking code to an existing API.  

Finally,  
we learned about extensible modules, and  
saw how we can use the techniques of dynamic module imports,  
plugins, and hooks to create a module that does more than you designed it to do.  
We saw that the dynamic nature of Python makes it ideally suited  
to the creation of extensible modules where the behavior of your modules  
is not completely defined at the time you write them.  

In the next chapter,  
we will learn how to design and implement modules  
that can be shared and reused in other programs.  

