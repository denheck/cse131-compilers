# CSE-131 Compilers

https://cseweb.ucsd.edu/classes/sp17/cse131-a/

## Quick Start

Build docker image:
```
docker build -t cse131-compilers .
```

Build and run app:
```
docker run -ti --rm -v`pwd`:/app cse131-compilers dune exec ./bin/app.exe
``` 

Start a utop REPL with project loaded:
```
docker run -ti --rm -v `pwd`:/app cse131-compilers dune utop
```
