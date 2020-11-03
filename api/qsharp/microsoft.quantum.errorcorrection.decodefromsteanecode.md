---
uid: Microsoft.Quantum.ErrorCorrection.DecodeFromSteaneCode
title: DecodeFromSteaneCode operation
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.ErrorCorrection
qsharp.name: DecodeFromSteaneCode
qsharp.summary: >-
  An inverse encoding operation that maps an unencoded quantum register to an encoded quantum
  register under the ⟦7, 1, 3⟧ Steane quantum code.
---

# DecodeFromSteaneCode operation

Namespace: [Microsoft.Quantum.ErrorCorrection](xref:Microsoft.Quantum.ErrorCorrection)

Package: [](https://nuget.org/packages/)


An inverse encoding operation that maps an unencoded quantum register to an encoded quantum

```qsharp
operation DecodeFromSteaneCode (logicalRegister : Microsoft.Quantum.ErrorCorrection.LogicalRegister) : (Qubit[], Qubit[])
```


## Input

### logicalRegister : [LogicalRegister](xref:Microsoft.Quantum.ErrorCorrection.LogicalRegister)

An array of qubits representing the encoded 5-qubit code logical state.



## Output : ([Qubit](xref:microsoft.quantum.lang-ref.qubit)[],[Qubit](xref:microsoft.quantum.lang-ref.qubit)[])

A qubit array of length 1 representing the unencoded state in the

## Remarks

The chosen decoder uses the CSS code property of the ⟦7, 1, 3⟧ Steane code, i.e., it corrects X errors

## References

- D. Gottesman, "Stabilizer Codes and Quantum Error Correction," Ph.D. Thesis, Caltech, 1997;

## See Also

- [Microsoft.Quantum.ErrorCorrection.SteaneCodeEncoder](xref:Microsoft.Quantum.ErrorCorrection.SteaneCodeEncoder)
- [Microsoft.Quantum.ErrorCorrection.SteaneCodeDecoder](xref:Microsoft.Quantum.ErrorCorrection.SteaneCodeDecoder)
- [Microsoft.Quantum.ErrorCorrection.LogicalRegister](xref:Microsoft.Quantum.ErrorCorrection.LogicalRegister)