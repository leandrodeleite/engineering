
---
@mojo/manual __  

---
Mojo Manual
| [mojo/manual](https://docs.modular.com/mojo/manual/)  
Complete guide.

Combine with:  
Mojo API reference
| [mojo/lib](https://docs.modular.com/mojo/lib/)  

Everything you need to write  
high-performance Mojo code for CPUs and GPUs.  

Docs on GitHub
| [mojo/docs ](https://github.com/modular/modular/tree/main/mojo/docs)  

Get Started with a tutorial
| [mojo/manual/get-started](https://docs.modular.com/mojo/manual/get-started/)  


## About Mojo

Systems programming language.  
Specifically designed for  
• High-performance AI infrastructure  
• Heterogeneous hardware.  


Built from the ground-up using MLIR.  
— *a modern compiler infrastructure  
for heterogeneous hardware,  
from CPUs to GPUs and other AI ASICs.*  
Meaning:  
*One language to write all your code,  
from high-level AI applications  
all the way down to low-level GPU kernels  
— without using any hardware-specific libraries  
(such as CUDA and ROCm).*  

Mojo vision
| [mojo/vision](https://docs.modular.com/mojo/vision/)


## Key features


---
Python syntax & interop
| [mojo/manual/python](https://docs.modular.com/mojo/manual/python/)

Pythonic syntax.  
*Fully integrates the existing Python ecosystem,  
including its wealth of AI and machine-learning libraries.*  

Mojo adopts (and extends) Python's syntax and integrates with existing Python code. Mojo's interoperability works in both directions, so you can import Python libraries into Mojo and create Mojo bindings to call from Python.  


All data types—including basic types such as String and Int—are defined as structs. No types are built into the language itself. That means you can define your own types that have all the the same capabilities as the standard library types.  
Structs, Struct-based types
| [mojo/manual/structs](https://docs.modular.com/mojo/manual/structs/)

Mojo's trait system solves the problem of static typing by letting you define a shared set of behaviors that types (structs) can implement. It allows you to write functions that depend on traits rather than specific types, similar to interfaces in Java or protocols in Swift, except with compile-time type checking and no run-time performance cost.  
Traits, Zero-cost Traits
| [mojo/manual/traits](https://docs.modular.com/mojo/manual/traits/)

Mojo's ownership system ensures that only one variable "owns" a specific value at a given time—such that Mojo can safely deallocate the value when the owner's lifetime ends—while still allowing you to share references to the value. This provides safety from errors such as use-after-free, double-free, and memory leaks without the overhead cost of a garbage collector.  
Ownership, Value ownership
| [mojo/manual/values](https://docs.modular.com/mojo/manual/values/)

Mojo's parameterization system enables powerful metaprogramming in which the compiler generates a unique version of a type or function based on parameter values, similar to C++ templates, but more intuitive.  
Parameterization, Compile-time metaprogramming
| [mojo/manual/parameters](https://docs.modular.com/mojo/manual/parameters/)

Mojo is designed from the ground up to support heterogeneous hardware—the Mojo compiler makes no assumptions about whether your code is written for CPUs, GPUs, or something else. Instead, hardware behaviors are handled by Mojo libraries, as demonstrated by types such as SIMD that allows you to write vectorized code for CPUs, and the gpu package that enables hardware-agnostic GPU programming.  
GPU programming, Hardware portability
| [mojo/manual/gpu/fundamentals](https://docs.modular.com/mojo/manual/gpu/fundamentals/)

