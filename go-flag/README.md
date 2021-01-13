# Usage

```
package main

import (
    "fmt"
    "github.com/cclin81922/go-3rd-party/go-flag"
)

func main() {
    port := flag.Int("port", 8080, "HTTP server port")
    flag.Parse()
    fmt.Printf("HTTP server port: %d\n",*port)
}
```
