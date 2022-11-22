# Memory and Data Semantics

## Variables

- Use var keyword to declare variables that are set to their zero value.

```go
var a int // use int rather than more specific types unless necessary
var b string
var c float64
var d bool
```

- Use the short variable declaration to declare and initialize a variable.

```go
a := "aaa"
```

### Conversion overcasting

- Conversion overcasting is specifying a type and performing a conversion. It is a lot safer

```go
a := int32(10)
```
