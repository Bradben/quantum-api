---
uid: Microsoft.Quantum.Synthesis.SingleQubitCliffordAsOperation
title: SingleQubitCliffordAsOperation function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Synthesis
qsharp.name: SingleQubitCliffordAsOperation
qsharp.summary: >-
  Returns a representation of a single-qubit Clifford operator as an
  operation acting on a single qubit.
---

# SingleQubitCliffordAsOperation function

Namespace: [Microsoft.Quantum.Synthesis](xref:Microsoft.Quantum.Synthesis)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns a representation of a single-qubit Clifford operator as an

```qsharp
function SingleQubitCliffordAsOperation (clifford : Microsoft.Quantum.Synthesis.SingleQubitClifford) : (Qubit => Unit is Adj + Ctl)
```


## Input

### clifford : [SingleQubitClifford](xref:Microsoft.Quantum.Synthesis.SingleQubitClifford)





## Output : [Qubit](xref:microsoft.quantum.lang-ref.qubit) => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Adj + Ctl

An operation that applies the given Clifford operator to a single

## Example

Suppose that `op` is a single-qubit Clifford operator, and that

## See Also

- [Microsoft.Quantum.Synthesis.Apply1C](xref:Microsoft.Quantum.Synthesis.Apply1C)