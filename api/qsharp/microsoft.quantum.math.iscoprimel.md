---
uid: Microsoft.Quantum.Math.IsCoprimeL
title: IsCoprimeL function
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: IsCoprimeL
qsharp.summary: Returns true if $a$ and $b$ are co-prime and false otherwise.
---

# IsCoprimeL function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns true if $a$ and $b$ are co-prime and false otherwise.

```qsharp
function IsCoprimeL (a : BigInt, b : BigInt) : Bool
```


## Input

### a : [BigInt](xref:microsoft.quantum.qsharp.valueliterals#bigint-literals)

the first number of which co-primality is being tested


### b : [BigInt](xref:microsoft.quantum.qsharp.valueliterals#bigint-literals)

the second number of which co-primality is being tested



## Output : [Bool](xref:microsoft.quantum.qsharp.valueliterals#bool-literals)

True, if $a$ and $b$ are co-prime (e.g. their greatest common divisor is 1 ),and false otherwise