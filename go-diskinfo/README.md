# Usage

```
package main

import (
    "fmt"
    "github.com/cclin81922/go-3rd-party/go-diskinfo"
)

func main() {
    disk := diskinfo.DiskUsage("/")
    fmt.Printf("All: %.2f GB %.2f GiB\n", float64(disk.All)/float64(diskinfo.GB), float64(disk.All)/float64(diskinfo.GiB))
    fmt.Printf("Used: %.2f GB %.2f GiB\n", float64(disk.Used)/float64(diskinfo.GB), float64(disk.All)/float64(diskinfo.GiB))
    fmt.Printf("Free: %.2f GB %.2f GiB\n", float64(disk.Free)/float64(diskinfo.GB), float64(disk.All)/float64(diskinfo.GiB))
}
```
