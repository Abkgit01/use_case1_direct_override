# use_case1_direct_override

## Purpose
Demonstrates a direct instruction that attempts to replace higher-priority behavior.

## Example Injection
$(System.Collections.Hashtable.Example)

## Risk Note
High risk because the malicious instruction is explicit and easy to execute.

## Files
- Program.cs prints the scenario summary and calculated risk score.
- Calculator.cs defines the scenario model and the scoring logic.
- CalculatorTests.cs contains simple validation helpers for the scenario.
