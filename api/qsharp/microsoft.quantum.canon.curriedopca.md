---
uid: Microsoft.Quantum.Canon.CurriedOpCA
title: CurriedOpCA function
ms.date: 2/23/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: CurriedOpCA
qsharp.summary: >-
  Returns a curried version of an operation on two inputs.

  That is, given an operation with two inputs, this function applies Curry's isomorphism
  $f(x, y) \equiv f(x)(y)$ to return an operation of one input which
  returns an operation of one input.
---

# CurriedOpCA function

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns a curried version of an operation on two inputs.

```qsharp
function CurriedOpCA<'T, 'U> (op : (('T, 'U) => Unit is Adj + Ctl)) : ('T -> ('U => Unit is Adj + Ctl))
```


## Input

### op : ('T,'U) => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Adj + Ctl

An operation whose input is a pair.



## Output : 'T -> 'U => [Unit](xref:microsoft.quantum.lang-ref.unit)  is Adj + Ctl

An operation which accepts the first element of a pair and returns

## Type Parameters

### 'T

The type of the first component of a function defined on pairs.
### 'U

The type of the second component of a function defined on pairs.

## Remarks

The following are equivalent:

## See Also

- [Microsoft.Quantum.Canon.CurriedOp](xref:Microsoft.Quantum.Canon.CurriedOp)
- [Microsoft.Quantum.Canon.CurriedOpC](xref:Microsoft.Quantum.Canon.CurriedOpC)
- [Microsoft.Quantum.Canon.CurriedOpA](xref:Microsoft.Quantum.Canon.CurriedOpA)