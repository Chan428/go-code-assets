# Short Variable Declaration

Inside a function (even the main function), the `:=` short assignment statement can be used in place of a `var` declaration. The `:=` operator infers the type of the new variable based on the value.

```go
var empty string
```

Is the same as


```go
empty := ""
```

```go
numCars := 10 // inferred to be an integer

temperature := 0.0 // temperature is inferred to be a floating point value because it has a decimal point

var isFunny = true // isFunny is inferred to be a boolean
```



## Assignment

A lot of our users send birthday messages using the textbook API.

Declare a variable named `congrats` with the value "happy birthday!" using a short variable declaration.
