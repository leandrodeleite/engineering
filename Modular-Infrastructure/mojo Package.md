
---
[mojo/manual/install](https://docs.modular.com/mojo/manual/install)


---
## `mojo` Package

`mojo` and `mojo-compiler`


---
**`mojo-compiler` Package**  

- `mojo` CLI
| [mojo/cli](https://docs.modular.com/mojo/cli/)  
- Mojo Standard library
| [mojo/lib](https://docs.modular.com/mojo/lib/)  
- `mojo` Python package
| [mojo/python/mojo](https://github.com/modular/modular/tree/main/mojo/python/mojo)  

Where only need to  
call or build existing Mojo code.  

*- Production environments*  
*- Programming in Python  
and  calling a mojo Package.*  


---
**`mojo` Package**

- Includes `mojo-compiler` list

- Mojo language server (LSP) for IDE/edito integration
- Mojo Debugger (includes LLDB)
| [mojo/tools/debugging](https://docs.modular.com/mojo/tools/debugging/)
- Mojo Code Formatter
| [mojo/cli/format](https://docs.modular.com/mojo/cli/format/)
- Mojo REPL
| [mojo/cli/repl](https://docs.modular.com/mojo/cli/repl/)

Everything needed for development..


---
## Install Mojo

As a Python Package,  
with:  

- `pixi`
- `uv`
- `pip`
- `conda`


`pixi`  
| [/pixi](https://docs.modular.com/pixi)  
*More Reliable experience*  

Both package manager and  
virtual environment manager.  
Fast, Language Agnostic.  
Lock files for package dependencies.  


---
## `pip` Commands

*Stable*
```sh
pip install mojo
```

*Nightly
```sh
pip install \ 
    --pre mojo \
    --index-url https://dl.modular.com/public/nightly/python/simple/
```

*Verify*
```
mojo --version
```

*Update*
```
pip install --upgrade mojo
```

*Uninstall*
```
pip uninstall mojo
```

