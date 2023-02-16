# Testing

Test function signature
- Must be in _test.go file
- func name must start with Test
- Must accept parameter whose type is *testing.T
- Don't return anything
- `t.Parallel()` is a standard statement/boilerplate for enabling test concurrency

want-and-got pattern

test cases, aka table tests, looping over a slice of structs (range) with the test data