---
uid: qdk.std.canon-toc
title: Std.Canon namespace
description: Table of contents for the Q# Canon namespace
author: bradben
ms.author: brbenefield
ms.date: 11/04/2024
ms.topic: landing-page
---

# Std.Canon

The Std.Canon namespace contains the following functions and operations:


| Name | Description |
|------|-------------|
| [ApplyCNOTChain](xref:Qdk.Std.Canon.ApplyCNOTChain) | Computes the parity of a register of qubits in-place. |
| [ApplyControlledOnBitString](xref:Qdk.Std.Canon.ApplyControlledOnBitString) | Applies `oracle` on `target` when `controlRegister` |
| [ApplyControlledOnInt](xref:Qdk.Std.Canon.ApplyControlledOnInt) | Applies a unitary operation on the target if the control |
| [ApplyP](xref:Qdk.Std.Canon.ApplyP) | Given a single-qubit Pauli operator, applies the corresponding operation |
| [ApplyPauli](xref:Qdk.Std.Canon.ApplyPauli) | Given a multi-qubit Pauli operator, applies the corresponding operation |
| [ApplyPauliFromBitString](xref:Qdk.Std.Canon.ApplyPauliFromBitString) | Applies a Pauli operator on each qubit in an array if the corresponding |
| [ApplyPauliFromInt](xref:Qdk.Std.Canon.ApplyPauliFromInt) | Applies a Pauli operator on each qubit in an array if the corresponding |
| [ApplyQFT](xref:Qdk.Std.Canon.ApplyQFT) | Applies the rotations of Quantum Fourier Transform (QFT) to a little-endian quantum register. |
| [ApplyToEach](xref:Qdk.Std.Canon.ApplyToEach) | Applies an operation to each element in a register. |
| [ApplyToEachA](xref:Qdk.Std.Canon.ApplyToEachA) | Applies an operation to each element in a register. |
| [ApplyToEachC](xref:Qdk.Std.Canon.ApplyToEachC) | Applies an operation to each element in a register. |
| [ApplyToEachCA](xref:Qdk.Std.Canon.ApplyToEachCA) | Applies an operation to each element in a register. |
| [ApplyXorInPlace](xref:Qdk.Std.Canon.ApplyXorInPlace) | Applies a bitwise-XOR operation between a classical integer and an |
| [ApplyXorInPlaceL](xref:Qdk.Std.Canon.ApplyXorInPlaceL) | Applies a bitwise-XOR operation between a classical integer and an |
| [CX](xref:Qdk.Std.Canon.CX) | Applies the controlled-X (CX) gate to a pair of qubits. |
| [CY](xref:Qdk.Std.Canon.CY) | Applies the controlled-Y (CY) gate to a pair of qubits. |
| [CZ](xref:Qdk.Std.Canon.CZ) | Applies the controlled-Z (CZ) gate to a pair of qubits. |
| [Fst](xref:Qdk.Std.Canon.Fst) | Given a pair, returns its first element. |
| [Relabel](xref:Qdk.Std.Canon.Relabel) | Relabels the qubits in the `current` array with the qubits in the `updated` array. The `updated` array |
| [Snd](xref:Qdk.Std.Canon.Snd) | Given a pair, returns its second element. |
| [SwapReverseRegister](xref:Qdk.Std.Canon.SwapReverseRegister) | Uses SWAP gates to reverse the order of the qubits in a register. |