# Interpreter Java

## File Structure
```css
interpreter-java
./
├── factorial.x
├── factorial.x.cod
├── fib.x
├── fib.x.cod
├── LICENSE
├── README.md
├── theinterpreter.pdf
├── interpreter/
│   ├── bytecode/
│   │   ├── AddressLabel.java
│   │   ├── ArgsCode.java
│   │   ├── BopCode.java
│   │   ├── ByteCode.java
│   │   ├── CallCode.java
│   │   ├── DumpCode.java
│   │   ├── FalseBranchCode.java
│   │   ├── GotoCode.java
│   │   ├── HaltCode.java
│   │   ├── LabelCode.java
│   │   ├── LitCode.java
│   │   ├── LoadCode.java
│   │   ├── PopCode.java
│   │   ├── ReadCode.java
│   │   ├── ReturnCode.java
│   │   ├── StoreCode.java
│   │   └── WriteCode.java
│   ├── ByteCodeLoader.java
│   ├── CodeTable.java
│   ├── Interpreter.java
│   ├── Program.java
│   ├── RunTimeStack.java
│   └── VirtualMachine.java
└── documentation/
    └── documentation.pdf
```

### Java Doc comments written in ByteCode classes and RunTimeStack class are taken from theinterpreter.pdf
### Credit goes to the author of theinterpreter.pdf
