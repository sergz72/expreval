# Go Expression Evaluator

Version: 0.01
MIT License (MIT)

go expression evaluator is a basic math expression parser and evaluator.

## Features

- Basic Math Operators like '+', '-', '*', '/'
- Operator precedence, Ex: 1+2*3 = 1+6 = 7
- grouping () Ex: (1+2)*3


## Basic usage

  const PARSER_STACK_SIZE = 100

  result, err := expreval.Eval("2+(3+4)*(4-8)", stackSize)
  if err != nil {
    ...
  }
  fmt.Printf("%v", result)
