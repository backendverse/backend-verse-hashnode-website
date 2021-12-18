## Hello World - Go by example

The following is the Go version of the Hello World program.

Go always begins the execution of the application with the code found in the `main()` function of the `main` package.

```go
package main

import "fmt"

func main() {
	fmt.Println("Hello World!")
}
```

Each Go source code begins with a `package` declaration. In this case, the name of the package is `main`, which has a special meaning in Go. 

The `import` keyword allows you to include functionality from existing packages. In our case, we only need some of the functionality of the `fmt` package to print the "Hello World!" message.



