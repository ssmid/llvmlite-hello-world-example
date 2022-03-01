# Hello world using llvmlite
An example on how to AOT-compile hello world with llvmlite

It is meant for unix and uses the system's C compiler for linking. (It needs the compiler's C runtime libraries and llvmlite does not provide any as far as I know, because it is meant for JIT-compilation.)

For JIT-compilation, see the official docs from llvmlite: https://llvmlite.readthedocs.io/en/latest/user-guide/binding/examples.html
