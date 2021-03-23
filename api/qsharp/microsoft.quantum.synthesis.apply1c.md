---
uid: Microsoft.Quantum.Synthesis.Apply1C
title: Apply1C operation
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Synthesis
qsharp.name: Apply1C
qsharp.summary: >-
  Given a single-qubit Clifford operator, applies the corresponding operation
  to a single qubit.
---

# Apply1C operation

Namespace: [Microsoft.Quantum.Synthesis](xref:Microsoft.Quantum.Synthesis)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Given a single-qubit Clifford operator, applies the corresponding operation

```qsharp
operation Apply1C (op : Microsoft.Quantum.Synthesis.SingleQubitClifford, target : Qubit) : Unit is Adj + Ctl
```


## Input

### op : [SingleQubitClifford](xref:Microsoft.Quantum.Synthesis.SingleQubitClifford)

The Clifford operator to be applied.


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

The qubit to which `op` is to be applied as an operation.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Example

The following are equivalent, as $ES\omega^5 = (HS^3\omega^3)S\omega^5