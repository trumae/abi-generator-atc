# Case 8

## ATC (Acceptance Test Criteria)
- Try to generate ABI spec file with a valid table of index type i128i128
- Verify ABI generator succeed
- Verify the ABI json file is as expected (abi-expected.json)

## Command Run
```
eosiocpp -g case8.abi types.hpp
```

## Result
```bash
Generated case8.abi ...
```

## Conclusion
Test Pass.
ABI generator succeed.
ABI file is generated as expected.
