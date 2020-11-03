---
uid: Microsoft.Quantum.Measurement.MResetX
title: MResetX operation
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Measurement
qsharp.name: MResetX
qsharp.summary: >-
  Measures a single qubit in the X basis,
  and resets it to a fixed initial state
  following the measurement.
---

# MResetX operation

Namespace: [Microsoft.Quantum.Measurement](xref:Microsoft.Quantum.Measurement)

Package: [](https://nuget.org/packages/)


Measures a single qubit in the X basis,

```qsharp
operation MResetX (target : Qubit) : Result
```


## Description

Performs a single-qubit measurement in the $X$-basis,

## Input

### target : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

A single qubit to be measured.



## Output : __invalid<Result>__

The result of measuring `target` in the Pauli $X$ basis.