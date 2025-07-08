# test - simple testing library for hoblang

`test` library provides convinient API for testing

## Usage

```hob
import test;

test.case("arithmetic should be good", fun () {
    if 1 != 1 {
        return false;
    }
    return true;
});
```
