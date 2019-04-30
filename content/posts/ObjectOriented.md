---
title: "Object Oriented"
date: 2019-04-26
draft: true
toc: false
images:
tags:
  - go
---

## Classes

In Go you don't need to declare explicit class definitions the way you do in Java. A class is defined implicitly by creating a set of methods with all operate on a shared type. For example:

```go

type Dog struct {
  Name  string
  Weight float64
  Age int64
}

func (d *Dog) GetDogYears() int64 {
	return d.Age * 7
}
```