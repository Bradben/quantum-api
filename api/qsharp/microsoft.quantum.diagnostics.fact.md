---
uid: Microsoft.Quantum.Diagnostics.Fact
title: Fact function
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Diagnostics
qsharp.name: Fact
qsharp.summary: Declares that a classical condition is true.
---

# Fact function

Namespace: [Microsoft.Quantum.Diagnostics](xref:Microsoft.Quantum.Diagnostics)

Package: [Microsoft.Quantum.QSharp.Foundation](https://nuget.org/packages/Microsoft.Quantum.QSharp.Foundation)


Declares that a classical condition is true.

```qsharp
function Fact (actual : Bool, message : String) : Unit
```


## Input

### actual : [Bool](xref:microsoft.quantum.qsharp.valueliterals#bool-literals)

The condition to be declared.


### message : [String](xref:microsoft.quantum.qsharp.valueliterals#string-literals)

Failure message string to be printed in the case that the classicalcondition is false.



## Output : [Unit](xref:microsoft.quantum.qsharp.valueliterals#unit-literal)



## Example

The following Q# snippet will fail:```qsharpFact(false, "Expected true.");```

## See Also

- [Microsoft.Quantum.Diagnostics.Contradiction](xref:Microsoft.Quantum.Diagnostics.Contradiction)