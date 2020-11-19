---
uid: Microsoft.Quantum.Preparation.PurifiedMixedStateWithData
title: PurifiedMixedStateWithData function
ms.date: 11/19/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: PurifiedMixedStateWithData
qsharp.summary: "Returns an operation that prepares a a purification of a given mixed\rstate, entangled with a register representing a given collection of data.\rA \"purified mixed state with data\" refers to a state of the form Σᵢ √\U0001D45Dᵢ |\U0001D456⟩ |\U0001D465ᵢ⟩ |garbageᵢ⟩,\rwhere each \U0001D465ᵢ is a bitstring encoding additional data associated with the register |\U0001D456⟩.\r\rSee https://arxiv.org/pdf/1805.03662.pdf?page=15 for further discussion."
---

# PurifiedMixedStateWithData function

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Returns an operation that prepares a a purification of a given mixed

```qsharp
function PurifiedMixedStateWithData (targetError : Double, coefficients : (Double, Bool[])[]) : Microsoft.Quantum.Preparation.MixedStatePreparation
```


## Description

Uses the Quantum ROM technique to represent a given density matrix,

## Input

### targetError : [Double](xref:microsoft.quantum.lang-ref.double)

The target error $\epsilon$.


### coefficients : ([Double](xref:microsoft.quantum.lang-ref.double),[Bool](xref:microsoft.quantum.lang-ref.bool)[])[]

Array of $N$ coefficients specifying the probability of basis states,



## Output : [MixedStatePreparation](xref:Microsoft.Quantum.Preparation.MixedStatePreparation)

An operation that prepares $\tilde \rho$ as a purification onto a joint

## Remarks

The coefficients provided to this operation are normalized following the

## References

- Encoding Electronic Spectra in Quantum Circuits with Linear T Complexity

## See Also

- [Microsoft.Quantum.Preparation.PurifiedMixedState](xref:Microsoft.Quantum.Preparation.PurifiedMixedState)