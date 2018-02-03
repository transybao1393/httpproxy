# A Go HTTP proxy library which has KISS principle

## Introduction

`github.com/go-httpproxy/httpproxy` repository provides an HTTP proxy library for Go (golang).

The library is regular HTTP proxy; supports HTTP, HTTPS through CONNECT. And also provides HTTPS connection using "Man in the Middle" style attack.

It's easy to use. `httpproxy.Proxy` implements `Handler` interface of `net/http` package to offer `http.ListenAndServe` function.

### Keep it simple, stupid!

> KISS is an acronym for "Keep it simple, stupid" as a design principle noted by the U.S. Navy in 1960. The KISS principle states that most systems work best if they are kept simple rather than made complicated; therefore simplicity should be a key goal in design and unnecessary complexity should be avoided. The phrase has been associated with aircraft engineer Kelly Johnson (1910–1990). The term "KISS principle" was in popular use by 1970. Variations on the phrase include: "Keep it simple, silly", "keep it short and simple", "keep it simple and straightforward", "keep it small and simple" and "keep it stupid, simple". [Wikipedia]

## Usage

```go
//
```

## GoDoc

[https://godoc.org/github.com/go-httpproxy/httpproxy](https://godoc.org/github.com/go-httpproxy/httpproxy)

## To-Do

* GoDoc
