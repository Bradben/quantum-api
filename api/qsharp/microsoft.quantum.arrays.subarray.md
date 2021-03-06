---
uid: Microsoft.Quantum.Arrays.Subarray
title: Subarray function
ms.date: 4/27/2021 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Subarray
qsharp.summary: >-
  Takes an array and a list of locations and
  produces a new array formed from the elements of the original
  array that match the given locations.
---

# Subarray function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Takes an array and a list of locations andproduces a new array formed from the elements of the originalarray that match the given locations.

```qsharp
function Subarray<'T> (indices : Int[], array : 'T[]) : 'T[]
```


## Input

### indices : [Int](xref:microsoft.quantum.qsharp.valueliterals#int-literals)[]

A list of integers that is used to define the subarray.


### array : 'T[]

An array of elements over `'T`.



## Output : 'T[]

An array `out` of elements whose indices correspond to the subarray,such that `out[idx] == array[indices[idx]]`.

## Type Parameters

### 'T

The type of `array` elements.

## Remarks

The function is defined for generic types, i.e., whenever we havean array `'T[]` and a list of locations `Int[]` defining the subarray.The construction of the subarray is a based on generating a new, deepcopy of the given array as opposed to maintaining references.If `Length(indices) < Length(array)`, this function will return asubset of `array`. On the other hand, if `indices` contains repeatedelements, the corresponding elements of `array` will likewise berepeated.If `indices` and `array` are the same length, this functionprovides permutations of `array`.