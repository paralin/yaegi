# Usage of `reflect` in the codebase

## `internal/unsafe2/go1_20_unsafe.go`

This file uses the `reflect` package to create and manipulate recursive struct types. It defines a `dummy` struct and a `DummyType` variable using `reflect.TypeOf`. The `SetFieldType` function uses `reflect` to set the type of a struct field at a given index.

## `internal/unsafe2/go1_21_unsafe.go`

Similar to `go1_20_unsafe.go`, this file uses the `reflect` package to create and manipulate recursive struct types. It defines a `dummy` struct and a `DummyType` variable using `reflect.TypeOf`. The `SetFieldType` function uses `reflect` to set the type of a struct field at a given index.

## `internal/unsafe2/unsafe_test.go`

This file uses the `reflect` package to test the manipulation of struct field types. It defines a test function `TestSwapFieldType` that uses `reflect.StructField` and `reflect.StructOf` to create a struct type and then uses `SetFieldType` to change the type of a field.

## `interp/interp.go`

This file uses the `reflect` package to handle interpreter values and types. It defines various functions and methods that use `reflect` to manipulate values and types during interpretation.

## `stdlib/go1_21_reflect.go`

This file contains the extracted symbols from the `reflect` package. It defines a map of `reflect` package symbols and their corresponding `reflect.Value` representations.

## `interp/scope.go`

This file uses the `reflect` package to manage scope and symbol types. It defines various functions and methods that use `reflect` to manipulate scope and symbol types during interpretation.

## `interp/value.go`

This file uses the `reflect` package to generate and manipulate values during interpretation. It defines various functions and methods that use `reflect` to create and modify values.

## `interp/build.go`

This file uses the `reflect` package to handle build constraints and tags. It defines various functions and methods that use `reflect` to manage build constraints and tags during interpretation.

## `interp/interp_test.go`

This file uses the `reflect` package to test interpreter functionalities. It defines various test functions that use `reflect` to verify the behavior of the interpreter.

## `interp/program.go`

This file uses the `reflect` package to handle program execution and compilation. It defines various functions and methods that use `reflect` to manage program execution and compilation during interpretation.
