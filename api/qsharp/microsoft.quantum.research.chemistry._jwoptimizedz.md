---
uid: Microsoft.Quantum.Research.Chemistry._JWOptimizedZ
title: _JWOptimizedZ operation
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Research.Chemistry
qsharp.name: _JWOptimizedZ
qsharp.summary: >-
  Applies a Rz rotation, with a C-NOT trick to double phase
  in phase estimation.
---

# _JWOptimizedZ operation

Namespace: [Microsoft.Quantum.Research.Chemistry](xref:Microsoft.Quantum.Research.Chemistry)

Package: [Microsoft.Quantum.Research.Chemistry](https://nuget.org/packages/Microsoft.Quantum.Research.Chemistry)


Applies a Rz rotation, with a C-NOT trick to double phasein phase estimation.

```qsharp
operation _JWOptimizedZ (angle : Double, parityQubit : Qubit, qubit : Qubit) : Unit is Adj + Ctl
```


## Input

### angle : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)

Angle of Rz rotation.


### parityQubit : [Qubit](xref:microsoft.quantum.qsharp.valueliterals#qubit-literals)

Qubit that determines the sign of time-evolution.


### qubit : [Qubit](xref:microsoft.quantum.qsharp.valueliterals#qubit-literals)





## Output : [Unit](xref:microsoft.quantum.qsharp.valueliterals#unit-literal)

