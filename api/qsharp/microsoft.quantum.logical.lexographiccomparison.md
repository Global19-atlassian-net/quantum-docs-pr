---
uid: Microsoft.Quantum.Logical.LexographicComparison
title: LexographicComparison function
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Logical
qsharp.name: LexographicComparison
qsharp.summary: >-
  Given a comparison function, returns a new function that
  lexographically compares two arrays.
---

# LexographicComparison function

Namespace: [Microsoft.Quantum.Logical](xref:Microsoft.Quantum.Logical)

Package: [](https://nuget.org/packages/)


Given a comparison function, returns a new function that

```qsharp
function LexographicComparison<'T> (elementComparison : (('T, 'T) -> Bool)) : (('T[], 'T[]) -> Bool)
```


## Input

### elementComparison : ('T,'T) -> [Bool](xref:microsoft.quantum.lang-ref.bool)

A function that compares two elements `x` and `y` and returns if



## Output : ('T[],'T[]) -> [Bool](xref:microsoft.quantum.lang-ref.bool)

A function that compares two arrays `xs` and `ys` and returns if

## Type Parameters

### 'T

The type of the elements of the arrays being compared.

## Remarks

The lexographic comparison between two arrays `xs` and `ys` is defined

## See Also

- [Microsoft.Quantum.Arrays.Sorted](xref:Microsoft.Quantum.Arrays.Sorted)