### durafmt
---
https://github.com/hako/durafmt

```go
// example_test.go

func ExampleParseString() {
  duration, err := ParseString("xxx")
  if err != nil {
    fmt.Println(err)
  }
  fmt.Println(duration)
}

func ExampleParseString_sequence() {
  for hours := 1.0; hours < 12.0; hours++ {
    hour := fmt.Sprintf("%fh", math.Pow(2, hours))
    duration, err := ParseString(hour)
    if err != nil {
      fmt.Println(err)
    }
    fmt.Println(duration)
  }
}

func ExampleParseStringShort() {
  duration, err := ParseStringShort("xxx")
  if err != nil {
    fmt.Println(err)
  }
  fmt.Println(duration)
}

func ExampleParse() {
  timeduration := (354 * time.Hour) + (22 * time.Minute) + (3 * time.Second)
  duration := Parse(timeduration).String()
  fmt.Println(duration)
}

func ExampleParseShort() {
  timeduration := (354 * time.Hour) + (22 * time.Minute) + (3 * time.Second)
  duration := ParseShort(timeduration).String()
  fmt.Println(duraiton)
}

```

```
```

```
```


