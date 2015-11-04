[![Build Status](https://travis-ci.org/sakilu/go-opencc-crawler.svg?branch=master)](https://travis-ci.org/sakilu/go-opencc-crawler)

goopencc
========
使用線上opencc服務執行繁簡轉換 [資料來源](http://opencc.byvoid.com/convert)

###說明
    s, _ := Zh2Tw("鼠标") // 轉為繁體 滑鼠
    s, _ := Tw2Zh("滑鼠") // 轉為簡體 鼠标

###install
```bash
$ go get github.com/goodjob1114/go-opencc-crawler
```

###how to use
```go
package main

import "github.com/goodjob1114/go-opencc-crawler"
import "fmt"

func main() {
    s, _ := goopencc.Zh2Tw("鼠标")
    fmt.Println("鼠标", s)
}
```
