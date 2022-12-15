# shellby - Simple Shell

A simple UNIX command interpreter written as part of the low-level programming and algorithm track at ALX - SE School.

## Description

**Shellby** is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes them.

### Environment
Upon invocation, **shellby** receives and copies the environment of the parent process in which it was executed. This environment is an array of *name-value* strings describing variables in the format *NAME=VALUE*. A few key environmental variables are:
* **HOME**
The home directory of the current user and the default directory argument for the **cd** builtin command.

* **PWD**
The current working directory as set by the **cd** command.

* **OLDPWD**
The previous working directory as set by the **cd** command.

* **PATH**
A colon-separated list of directories in which the shell looks for commands. A null directory name in the path (represented by any of two adjacent colons, an initial colon, or a trailing colon) indicates the current directory.

### Comments
**Shellby** ignores all words and characters preceeded by a `#` character on a line.

## Authors
* Chukwu Godgive <[Lawson](https://github.com/Chukwu-Godgive)> - ALX - Software Engineering Student
* Abdul-Lateef Gbadamosi <[Kehinde](https://github.com/Callkehinde)> - ALX - Software Engineering Student
