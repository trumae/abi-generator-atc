# Case 16
- Try to generate ABI spec file with ABI annotations in a multi-line comment 
- Verify ABI generator succeed
- Verify the ABI json file is as expected (abi-expected.json)

## ATC (Acceptance Test Criteria)

## Command Run
```
eosiocpp -g case16.abi types.hpp
```

## Result
```bash
Generated case16.abi ...
```

## Conclusion
Test Pass.
ABI generator succeed.
ABI file is generated as expected.
