## Installation

Run next command:

```bash
echo 'hello world'
```

## Launching

### Setup code

Save next code to file *main.go*

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

### Build Code

```bash
go mod init example
go mod tidy
go build -o example main.go
```

## Callouts

{% success This is the title %}

And this is the content!

So much space for activities!

{% end %}
