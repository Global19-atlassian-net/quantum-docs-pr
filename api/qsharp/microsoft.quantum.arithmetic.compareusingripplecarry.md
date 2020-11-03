---
uid: Microsoft.Quantum.Arithmetic.CompareUsingRippleCarry
title: CompareUsingRippleCarry operation
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Arithmetic
qsharp.name: CompareUsingRippleCarry
qsharp.summary: >-
  This operation tests if an integer represented by a register of qubits
  is greater than another integer, applying an XOR of the result onto an
  output qubit.
---

# CompareUsingRippleCarry operation

Namespace: [Microsoft.Quantum.Arithmetic](xref:Microsoft.Quantum.Arithmetic)

Package: [](https://nuget.org/packages/)


This operation tests if an integer represented by a register of qubits

```qsharp
operation CompareUsingRippleCarry (x : Microsoft.Quantum.Arithmetic.LittleEndian, y : Microsoft.Quantum.Arithmetic.LittleEndian, output : Qubit) : Unit
```


## Description

Given two integers `x` and `y` stored in equal-size qubit registers,

## Input

### x : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

First number to be compared stored in `LittleEndian` format in a qubit register.


### y : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

Second number to be compared stored in `LittleEndian` format in a qubit register.


### output : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Qubit that stores the result of the comparison $x>y$.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## References

- A new quantum ripple-carry addition circuit