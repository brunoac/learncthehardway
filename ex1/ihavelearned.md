# CFLAGS
CFLAGS and CXXFLAGS are environment variables whose content is passed on to each invocation of cc (the C compiler, usually gcc) or c++ (the C++ compiler, usually g++) respectively during compile and build phases of softwar

```sh
$ export CFLAGS="-Wall"
```

# Printing enviroment variable
```sh
$ printenv VARIABLE
```
```sh
$ echo $VARIABLE
```

# -Wall
-Wall enables all compiler's warning messages. This option should always be used, in order to generate better code.
