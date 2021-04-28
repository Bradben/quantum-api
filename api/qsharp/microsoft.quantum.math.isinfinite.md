---
uid: Microsoft.Quantum.Math.IsInfinite
title: IsInfinite function
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: IsInfinite
qsharp.summary: >-
  Returns whether a given floating-point value is either positive or
  negative infinity.
---

# IsInfinite function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

Package: [Microsoft.Quantum.QSharp.Foundation](https://nuget.org/packages/Microsoft.Quantum.QSharp.Foundation)


Returns whether a given floating-point value is either positive or

```qsharp
function IsInfinite (d : Double) : Bool
```


## Input

### d : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)

The floating-point value to be checked.



## Output : [Bool](xref:microsoft.quantum.qsharp.valueliterals#bool-literals)



## Example

```qsharp

## Remarks

`NaN()` is not a number, and is thus neither a finite number nor