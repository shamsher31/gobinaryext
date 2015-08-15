# gobinext
List of binary file extensions for Go

# How to install
<pre>
go get github.com/shamsher31/gobinext
</pre>

# How to use
<pre>
package main

import (
	"fmt"
	"github.com/shamsher31/gobinext"
)

func main() {
	fmt.Println(binext.Get())
}
</pre>

# Why
This package is inspired by [sindresorhus](https://www.npmjs.com/package/binary-extensions) npm module for Binary extension.

# License
MIT © [Shamsher Ansari](https://github.com/shamsher31)
