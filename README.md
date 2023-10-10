# Siemens-DebuggingLogging-A1


## Debugging steps:

All I needed was 5mins to run the program one time, and notice that the matrix multiplication isn't correct.

I checked it and found that all I needed to do is to write "+=" instead of "=" in line 43 in order to get the sum of all multiplied components, not the last one alone.

So, I didn't need to do use breakpoints, debugging or logging techniques.

However, I included the debugging command which can be used to debug.


## Instructions


### Download


```shell
git clone https://github.com/RoniEmad/Siemens-DebuggingLogging-A1.git
cd Siemens-DebuggingLogging-A1/
```

### Build

To build this project, you can use the following command:

```shell
g++ -g Matrix.cpp -o matrix
```
### Run
```shell
./matrix
```
### Debug
```shell
gdb matrix
```
