---
uid: Microsoft.Quantum.Convert.MaybeBigIntAsInt
title: MaybeBigIntAsInt function
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Convert
qsharp.name: MaybeBigIntAsInt
qsharp.summary: >-
  Converts a given big integer to an equivalent integer, if possible.
  The function returns a pair of the resulting integer and a Boolean flag
  which is true, if and only if the conversion was possible.
---

# MaybeBigIntAsInt function

Namespace: [Microsoft.Quantum.Convert](xref:Microsoft.Quantum.Convert)

Package: [Microsoft.Quantum.QSharp.Foundation](https://nuget.org/packages/Microsoft.Quantum.QSharp.Foundation)


Converts a given big integer to an equivalent integer, if possible.The function returns a pair of the resulting integer and a Boolean flagwhich is true, if and only if the conversion was possible.

```qsharp
function MaybeBigIntAsInt (a : BigInt) : (Int, Bool)
```


## Input

### a : [BigInt](xref:microsoft.quantum.qsharp.valueliterals#bigint-literals)





## Output : ([Int](xref:microsoft.quantum.qsharp.valueliterals#int-literals),[Bool](xref:microsoft.quantum.qsharp.valueliterals#bool-literals))



## Remarks

See [C# BigInteger constructor](https://docs.microsoft.com/dotnet/api/system.numerics.biginteger.-ctor?view=netframework-4.7.2#System_Numerics_BigInteger__ctor_System_Int64_) for more details.