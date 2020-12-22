# Usage

```
package main

import (
    "fmt"
    "github.com/cclin81922/go-3rd-party/go-diskinfo"
)

func main() {
    disk := DiskUsage("/")
    fmt.Printf("All: %.2f GB %.2f GiB\n", float64(disk.All)/float64(GB), float64(disk.All)/float64(GiB))
    fmt.Printf("Used: %.2f GB %.2f GiB\n", float64(disk.Used)/float64(GB), float64(disk.All)/float64(GiB))
    fmt.Printf("Free: %.2f GB %.2f GiB\n", float64(disk.Free)/float64(GB), float64(disk.All)/float64(GiB))
}
```
