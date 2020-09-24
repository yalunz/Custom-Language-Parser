## Run Parser

```sh
javacc .jj
```

```sh
javac *.java
```

```sh
java Assignment < test.txt
```
A PLM program consists of lines of code that define functions.

```sh
DEF ADDFOUR x { x+4 } ;
```

A MAIN Function must also be defined somewhere.

```sh
DEF MAIN { 1+ADDFOUR(2+ADDFOUR(3)) } ; 
DEF ADDFOUR x { x+4 } ;
```


