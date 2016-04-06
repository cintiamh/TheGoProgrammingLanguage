# Tutorial

## Hello, World!

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

Go is a compiled language. The `go` command has a number of subcommands. The simplest one is `run`, which compiles the source code from one or more source files whose names end in `.go`, links it with libraries, then runs the resulting executable file.

```
$ go run helloworld.go
```

If you want to compile it once and save the compiled result for later use, run with `go build`:

```
$ go build helloworld.go
```

This creates an executable binary file called helloworld that can be run any time without further processing.

```
$ ./helloworld
```
