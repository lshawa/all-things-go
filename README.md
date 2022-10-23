## What's the purpose of GO? 
1. Infrastructure 
a. Go was designed to run on multiple cores and built to support concurrency. Multithreading
- Multicore processors became common. 
- Big networked clusters became universal. 
- Most languages couldn't help in writing apps that'll take advantage of those infrastructure improvments. 
- You had apps that would execute one at a time but Go allows for doing multiple tasks at once. 
- Multithreading: 
    - You can have multiple tasks occur at once. 
    - For example: 
    a. We can have multuple users editing a document all at once. 

## Characteristics of GO 
1. It's a compuled language into a single binary. 

## GO Workspace Setup
1. Install GO 

## How to execute a go file? 
Compules and runs the code: 
```bash 
go run <file name?>
```

## Variables and Constants 
Variables are used to store values. 

```go 
var name = "Go Conference"
```

## Data Types in Go 
Two most basic types: 
1. Strings 
- Strings are used for textual data. Defined with double quotes. 
2. Integers
- Represent who numbers, positive and negative. 

Go is a statically typed language. You need to tell the Go compiler, the data type when declaring the variable. BUT Go can *infer* the tpe when you assign the value. 

Example: 

```go 
	var userName string
	var userTickets int
```