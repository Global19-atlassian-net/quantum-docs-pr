---
uid: Microsoft.Quantum.Synthesis.ApplyPermutationUsingDecomposition
title: ApplyPermutationUsingDecomposition operation
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Synthesis
qsharp.name: ApplyPermutationUsingDecomposition
qsharp.summary: >-
  Permutes the amplitudes in a quantum state given a permutation
  using decomposition-based synthesis.
---

# ApplyPermutationUsingDecomposition operation

Namespace: [Microsoft.Quantum.Synthesis](xref:Microsoft.Quantum.Synthesis)

Package: [](https://nuget.org/packages/)


Permutes the amplitudes in a quantum state given a permutation

```qsharp
operation ApplyPermutationUsingDecomposition (perm : Int[], qubits : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit
```


## Description

This procedure implements the decomposition based

## Input

### perm : [Int](xref:microsoft.quantum.lang-ref.int)[]

A permutation of $2^n$ elements starting from 0.


### qubits : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

A list of $n$ qubits to which the permutation is applied to.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## References

- [*Alexis De Vos*, *Yvan Van Rentergem*,

## See Also

- [Microsoft.Quantum.Synthesis.ApplyPermutationUsingDecompositionWithVariableOrder](xref:Microsoft.Quantum.Synthesis.ApplyPermutationUsingDecompositionWithVariableOrder)
- [Microsoft.Quantum.Synthesis.ApplyPermutationUsingTransformation](xref:Microsoft.Quantum.Synthesis.ApplyPermutationUsingTransformation)