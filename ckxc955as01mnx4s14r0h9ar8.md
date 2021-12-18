## Hello World - Go by example

The following is the Go version of the Hello World program.

Go always begins the execution of the application with the code found in the `main()` function of the `main` package.

If you are creating an executable application and not just a package that will be shared by other applications or packages, you should name your package `main`.

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello World!")
}
```

Each Go source code begins with a `package` declaration. In this case, the name of the package is `main`, which has a special meaning in Go. 

The `import` keyword allows you to include functionality from existing packages. In our case, we only need some of the functionality of the `fmt` package to print the "Hello World!" message.

Save it in a "hello.go" file, and run the program with the following command:

```bash
go run hello.go
```


