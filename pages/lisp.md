#  Lisp
### Brief History
Lisp is a programming language invented in the 1960 by John McCarthy. Lisp is noteable for it's involvement in early artifical intellegence research and very distinve sytnax. There are many variants of Lisp todays, such as Common Lisp, Scheme and Clojure.

<img style="float: right; width:30%; height:50%; object-fit:contain;" src="https://upload.wikimedia.org/wikipedia/commons/4/48/Lisp_logo.svg">

# Features
### Applications/Use-cases
The syntax of Lisp is heavily inspired by lambda calculus. It is noticebly different from other
programming languages and sometimes jokingly called parentheses hell.

An important concept of Lisp is the S-expression. All programs, and data structures are writted as S-expressions.
This give the language the property of being homoiconic, program and data is one and the same. This allows for powerful 
metaprogramming.

Unlike other language all operators in Lisp use postfix notations (also sometimes called polish notation).
For example `1+2` would be written as `(+ 1 2 )`

### Downsides/Difficulties

# Ecosystem

You can find instruction for installing Common Lisp [here](https://lisp-lang.org/learn/getting-started/)

Common Lisp uses Quicklisp as it's package manager.

Almost any implementation of Lisp feature interoperabllity with C, allow you to write call C code from Lisp.
# Examples

```lisp
;The following is written in Common Lisp

(print (+ 1 2 3)) ; print 6
```

# Stats

|           | Used by | Loved*| Hated*|
|-----------| ------- |--     | --    |
| Lisp      | 1.51%    | 57.19% | 42.81% |
| Clojure   | 1.31%    | 75.46% | 24.54% |

\* Out of the developer who currently work with this language, how many (wish/do not wish) to continue working with this language. 

# Sources
Stats from https://survey.stackoverflow.co/2022/#technology-most-popular-technologies
