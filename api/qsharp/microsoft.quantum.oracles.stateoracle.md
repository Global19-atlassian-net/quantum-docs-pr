---
uid: Microsoft.Quantum.Oracles.StateOracle
title: StateOracle user defined type
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: udt
qsharp.namespace: Microsoft.Quantum.Oracles
qsharp.name: StateOracle
qsharp.summary: >-
  Represents an oracle for state preparation.

  The inputs to the oracle $O$ are:

  - An integer indexing the flag qubit $f$.
  - The system register $s$ that will store the desired quantum state $\ket{\psi}\_s$.
---

# StateOracle user defined type

Namespace: [Microsoft.Quantum.Oracles](xref:Microsoft.Quantum.Oracles)

Package: [](https://nuget.org/packages/)


Represents an oracle for state preparation.

```qsharp

newtype StateOracle = (((Int, Qubit[]) => Unit is Adj + Ctl));
```



## Remarks

This oracle defined by