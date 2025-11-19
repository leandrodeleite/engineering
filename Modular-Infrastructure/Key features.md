
---
@mojo/manual __  


---
Links

- Docs on GitHub  
| [mojo/docs ](https://github.com/modular/modular/tree/main/mojo/docs)  

- Get started with Mojo  
| [mojo/manual/get-started](https://docs.modular.com/mojo/manual/get-started/)  
*Install Mojo and learn the language basics  
by building a complete Mojo program*  

- Get started with GPU programming  
| [mojo/manual/gpu/intro-tutorial](https://docs.modular.com/mojo/manual/gpu/intro-tutorial/)  
*Learn the basics of GPU programming with Mojo*  

- GPU Puzzles  
| [puzzles.modular.com](https://puzzles.modular.com/introduction.html)  
*Learn to program GPUs in Mojo  
by solving increasingly complex challenges*  

- Code examples  
| [examples/mojo](https://github.com/modular/modular/tree/main/examples/mojo)  
*Browse a wide range of Mojo code examples on GitHub*

- Community  
| [/community](https://www.modular.com/community)  
*Chat with us and the community  
in our forum and Discord channels*

- Using AI coding assistants with Mojo  
| https://docs.modular.com/max/coding-assistants/


---

## Mojo Manual

Complete guide.  
**Mojo Manual**  
| [mojo/manual](https://docs.modular.com/mojo/manual/)  

Combine with:  
**Mojo API reference**  
| [mojo/lib](https://docs.modular.com/mojo/lib/)  
*Mojo standard library and other references*

Everything you need to write  
high-performance Mojo code for CPUs and GPUs.  


---

## About Mojo

Systems programming language.  
Specifically designed for  
• High-performance AI infrastructure  
• Heterogeneous hardware.  


Mojo vision  
| [mojo/vision](https://docs.modular.com/mojo/vision/)


---
## Key features

- Python syntax & interop  
- Structs, Struct-based types  
- Traits, Trait system, Zero-cost Traits  
- Ownership system, Value ownership  
- Parameterization, Compile-time metaprogramming  
- GPU programming, Hardware portability; MLIR  


---
**Python syntax & interop**  
| [mojo/manual/python](https://docs.modular.com/mojo/manual/python/)

Pythonic syntax.  
*Fully integrates the existing Python ecosystem,  
including its wealth of AI and machine-learning libraries.*  

Adopts (and extends) Python's syntax.  
Integrates with existing Python code.  

*Interoperability works in both directions:  
• Import Python libraries into Mojo.  
• Create Mojo bindings to call from Python.*  

---
**Structs, Struct-based types**  
| [mojo/manual/structs](https://docs.modular.com/mojo/manual/structs/)

All data types are defined as structs.  
— including basic types such as `String` and `Int`.  
No types are built into the language itself.  

*That means you can define your own types  
that have all the the same capabilities  
as the standard library types.*  

---
**Traits, Trait system, Zero-cost Traits**  
| [mojo/manual/traits](https://docs.modular.com/mojo/manual/traits/)

Solves the problem of static typing  
by letting you define a shared set of behaviors  
that types (structs) can implement.  

*It allows you to write functions  
that depend on traits rather than specific types,  
similar to interfaces in Java or protocols in Swift,  
except with compile-time type checking and  
no run-time performance cost.*  

---
**Ownership system, Value ownership**  
| [mojo/manual/values](https://docs.modular.com/mojo/manual/values/)

Ensures that only one variable "owns"  
a specific value at a given time  
— such that Mojo can safely deallocate the value  
when the owner's lifetime ends  
— while still allowing you to share references to the value.  

*This provides safety from errors  
such as use-after-free, double-free, and memory leaks  
without the overhead cost of a garbage collector.*  

---
**Parameterization, Compile-time metaprogramming**  
| [mojo/manual/parameters](https://docs.modular.com/mojo/manual/parameters/)

Parameterization system  
enables powerful metaprogramming.  

*Compiler generates a unique version   
of a type or function  
based on parameter values,  
similar to C++ templates, but more intuitive.*  

---
**GPU programming, Hardware portability**  
| [mojo/manual/gpu/fundamentals](https://docs.modular.com/mojo/manual/gpu/fundamentals/)

Mojo is designed from the ground up  
to support heterogeneous hardware  
— the Mojo compiler makes no assumptions  
about whether your code is written for  
CPUs, GPUs, or something else.  

*Instead,  
hardware behaviors are handled by Mojo libraries,  
as demonstrated by types such as:  
• `SIMD` that allows you to write vectorized code for CPUs,   
• `gpu` package that enables hardware-agnostic GPU programming.*  


**MLIR**  
Built from the ground-up using MLIR.  
— *a modern compiler infrastructure  
for heterogeneous hardware,  
from CPUs to GPUs and other AI ASICs.*  

*One language to write all your code,  
from high-level AI applications  
all the way down to low-level GPU kernels  
— without using any hardware-specific libraries  
(such as CUDA and ROCm).*  

