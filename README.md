# ktools
My personaly tools for sport programming.

## Scripts
### knew
Create a new project which includes:
    * A source `src.cc` file.
    * An input `in.txt` file.
    * An expected output `exp.txt` file.

```
$ knew solution
$ cd solution
$ ls

exp.txt  in.txt  src.cc
```

### ktest
When you finished writing the solution and provided test cases in `in.txt` and
expected output `exp.txt`. Then run

```
knew
```

Possible output
```
Compiling	1.026
Executing	0.002
Comparing...
PASSED!
```
or
```
Compiling	1.026
Executing	0.002
Comparing...
PASSED!
```

## Installation
```
./install.sh
```
