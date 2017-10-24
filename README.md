# crc7
Sample code

```
package main

import(
        "fmt"
        "github.com/JulianDuniec/crc7"
)

func main() {
        data := []byte{0x01,0x02,0x03}
        hash := crc7.ComputeHash(data)
        fmt.Println(hash)
}
```
