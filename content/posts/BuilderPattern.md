---
title: "Builder Pattern"
date: 2019-04-26
draft: true
toc: false
images:
tags:
  - software
  - design patterns
  - creational patterns
---
The Builder Pattern allows you to separate the contruction of a complex object from it's representation so the same contruction process can create different representations.

## Example Implementation 

```go

package plane

type Speed float64

const (
	MPH Speed = 1
	KPH       = 1.609344
)

type Color string

const (
	White Color = "white"
	Blue        = "blue"
	Green       = "green"
)

type Builder interface {
	Color(Color) Builder
	TopSpeed(Speed) Builder
	Build() Interface
}

type Interface interface {
	TakeOff() error
	Fly() error
	Land() error
}


```

## Usage

```go

assembly :=  plane.NewBuilder()

privateJet := assembly.Color(White).TopSpeed(550 * plane.MPH).Build()
privateJet.TakeOff()
privateJet.Fly()
privateJet.Land()

```