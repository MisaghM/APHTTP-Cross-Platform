
# APHTTP Cross-Platform

A fork of **[ATHTTP](https://github.com/UTAP/APHTTP)** to make it cross-platform.  
Made for a [pull request](https://github.com/UTAP/APHTTP/pull/6).

## Changes

- **server/server.hpp/cpp**
  
  The socket part and small fixes.

- **utils/utilities.cpp**

  `readFile` and `writeObjectToFile`.

- **template_parser.hpp/cpp**

  To run Windows system commands.

- **makefile**

  Link `Ws2_32` on Windows.

- **examples/main.cpp**

  Catch exception by reference.

## References

Some useful references on cross-platform socket programming:  
[Hands-On Network Programming](https://handsonnetworkprogramming.com/articles/differences-windows-winsock-linux-unix-bsd-sockets-compatibility/)  
[This Stack Overflow answer](https://stackoverflow.com/a/28031039)  
[This github gist](https://gist.github.com/roxlu/3709838)
