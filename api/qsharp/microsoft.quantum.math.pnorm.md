---
uid: Microsoft.Quantum.Math.PNorm
title: PNorm function
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: PNorm
qsharp.summary: >-
  Returns the `L(p)` norm of a vector of `Double`s.

  That is, given an array $x$ of type `Double[]`, this returns the $p$-norm
  $\|x\|\_p= (\sum_{j}|x_j|^{p})^{1/p}$.
---

# PNorm function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns the `L(p)` norm of a vector of `Double`s.That is, given an array $x$ of type `Double[]`, this returns the $p$-norm$\|x\|\_p= (\sum_{j}|x_j|^{p})^{1/p}$.

```qsharp
function PNorm (p : Double, array : Double[]) : Double
```


## Input

### p : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)

The exponent $p$ in the $p$-norm.


### array : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)[]





## Output : [Double](xref:microsoft.quantum.qsharp.valueliterals#double-literals)

The $p$-norm $\|x\|_p$.