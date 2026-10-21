# TinyLisp — Silver Haired Lisp

A lightweight and practical Lisp dialect where your Common Lisp experience transfers directly.  
Powered by Java 25 virtual threads, it's ready to use simply by extracting a ZIP archive.

## Features

* **Runs introductory Common Lisp code with almost zero changes**  
  Currently developed using uLisp (MIT License) test suites as a benchmark.  
  *(Note: uLisp is a lightweight Lisp implementation for microcontrollers: http://www.ulisp.com/)*

* **A practical subset, not "everything" in Common Lisp**  
  Small learning curve and ready to use immediately.  
  Designed so your existing Common Lisp knowledge remains fully applicable.

* **Adopts a few convenient Clojure syntaxes**  
  Braces `{}` and brackets `[]` are supported.  
  Brings a touch of Clojure's expressive power into the Common Lisp world.

* **Lightweight concurrency with Java 25 Virtual Threads**  
  Easily spawn massive numbers of threads with a simple implementation.  
  Great for experimenting with concurrent programming.

* **Experimental Java Source Code Compiler**  
  ```lisp
  (defun foo (x) (+ x 2))
  (compile 'foo)
```



# Running compile generates Java source code, which can then be built with javac.

The generated .class files can be loaded back into TinyLisp.

Supports Telnet connections alongside standard I/O

Supports multiple sessions, making it convenient for verifying multi-threaded behavior.

# Goals
To provide an implementation where Common Lisp users can say:

"I can use Lisp on Java without having to learn all new concepts like in Clojure."

Provide a subset of Common Lisp implemented on Java that is far easier to learn for experienced Common Lisp developers than Clojure.


# Java Compilation Example (Experimental)


(defun foo (x) (+ x 2))
(compile 'foo)


# Launching (Planned)

Command names are subject to change based on implementation.

.bat for Windows

.sh bundled for macOS


# Installation

## Install Java 25.

## Download the TinyLisp ZIP archive.

## Extract it to any folder.

## Navigate to the installation directory:

    Windows: Launch via winshl1021.ps

    macOS: Run the shllog.sh and shlmac.sh  script

For more detailed syntax and current limitations, please refer to the separate documentation (xxxx.md) within the GitHub repository.

# Feedback

We plan to use GitHub Discussions.

Questions, ideas, and casual chat are all welcome!

# License

Custom License (written in both Japanese and English).

The Japanese version serves as the governing original text.




