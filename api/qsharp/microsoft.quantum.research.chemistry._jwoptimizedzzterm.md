---
uid: Microsoft.Quantum.Research.Chemistry._JWOptimizedZZTerm
title: _JWOptimizedZZTerm operation
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Research.Chemistry
qsharp.name: _JWOptimizedZZTerm
qsharp.summary: Applies time-evolution by a ZZ term described by a `GeneratorIndex`.
---

# _JWOptimizedZZTerm operation

Namespace: [Microsoft.Quantum.Research.Chemistry](xref:Microsoft.Quantum.Research.Chemistry)

Package: [Microsoft.Quantum.Research.Chemistry](https://nuget.org/packages/Microsoft.Quantum.Research.Chemistry)


Applies time-evolution by a ZZ term described by a `GeneratorIndex`.

```qsharp
operation _JWOptimizedZZTerm (term : Microsoft.Quantum.Simulation.GeneratorIndex, stepSize : Double, parityQubit : Qubit, qubits : Qubit[]) : Unit is Adj + Ctl
```


## Input

### term : [GeneratorIndex](xref:Microsoft.Quantum.Simulation.GeneratorIndex)

`GeneratorIndex` representing a ZZ term.


### stepSize : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)

Duration of time-evolution.


### parityQubit : [Qubit](xref:microsoft.quantum.qsharp.valueliterals#qubit-literals)

Qubit that determines the sign of time-evolution.


### qubits : [Qubit](xref:microsoft.quantum.qsharp.valueliterals#qubit-literals)[]

Qubits of Hamiltonian.



## Output : [Unit](xref:microsoft.quantum.qsharp.valueliterals#unit-literal)

