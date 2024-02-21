---
uid: Microsoft.Quantum.ResourceEstimation.CczCount
title: CczCount function
ms.date: 02/21/2024 12:00:00 AM
ms.topic: managed-reference
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.ResourceEstimation
qsharp.name: CczCount
qsharp.summary: Returns a tuple that can be passed to the `AccountForEstimates` operation
to specify that the number of the CCZ gates is equal to the `amount`.
---

# CczCount function

Namespace: [Microsoft.Quantum.ResourceEstimation](xref:Microsoft.Quantum.ResourceEstimation)

```qsharp
function CczCount(amount : Int) : (Int, Int)
```

## Summary
Returns a tuple that can be passed to the `AccountForEstimates` operation
to specify that the number of the CCZ gates is equal to the `amount`.