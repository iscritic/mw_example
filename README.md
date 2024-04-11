# Middleware (2 hours time limit)

This project implements a backend solution in Go with a focus on creating a handler to calculate the number of days left until January 1, 2025, and a middleware to verify user roles.

## Overview

The project includes the following components:
```
.
├── handler.go    
├── middleware.go    
└── main.go          
```

## Objective

The objective is to create a backend solution in Go within a two-hour time frame. The task includes implementing a handler to calculate the number of days left until January 1, 2025, and responding with an HTTP 200 OK status code. Additionally, a middleware should be developed to verify if the HTTP header User-Role is present and contains the value admin. If this condition is met, the middleware will print "red button user detected" to the console.

## Instructions
- back-end must be written in go
- You can use all third-party go packages
- Follow good coding practices
