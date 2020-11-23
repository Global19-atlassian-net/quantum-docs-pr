---
uid: Microsoft.Quantum.Canon.LogicalANDMeasAndFix
title: LogicalANDMeasAndFix operation
ms.date: 10/26/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: LogicalANDMeasAndFix
qsharp.summary: Computes the logical AND of multiple qubits.
---

# LogicalANDMeasAndFix operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Computes the logical AND of multiple qubits.

```qsharp
operation LogicalANDMeasAndFix (ctrlRegister : Qubit[], target : Qubit) : Unit
```


## Input

### ctrlRegister : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

Qubits input to the multiple-input AND gate.


### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

Qubit on which output of AND is written to. This is



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

When `ctrlRegister` has exactly $2$ qubits,

## References

- [ *Craig Gidney*, 1709.06648](https://arxiv.org/abs/1709.06648)