# Case 4

## ATC (Acceptance Test Criteria)
- Try to generate ABI spec file with two valid actions that share the same interface (struct) 
- Verify ABI generator succeed
- Verify the ABI json file is as expected (abi-expected.json)

## Command Run
```
eosiocpp -g case4.abi types.hpp
```

## Result
```bash
Generated case4.abi ...
```

## Conclusion
Test Pass.
ABI generator succeed.
ABI file is generated as expected.
