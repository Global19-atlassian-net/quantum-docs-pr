---
uid: Microsoft.Quantum.Arrays.Zipped
title: Zipped function
ms.date: 11/3/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: Zipped
qsharp.summary: >-
  Given two arrays, returns a new array of pairs such that each pair
  contains an element from each original array.
---

# Zipped function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [](https://nuget.org/packages/)


Given two arrays, returns a new array of pairs such that each pair

```qsharp
function Zipped<'T, 'U> (left : 'T[], right : 'U[]) : ('T, 'U)[]
```


## Input

### left : 'T[]

An array containing values for the first element of each tuple.


### right : 'U[]

An array containing values for the second element of each tuple.



## Output : ('T,'U)[]

An array containing pairs of the form `(left[idx], right[idx])` for

## Type Parameters

### 'T

The type of the left array elements.
### 'U

The type of the right array elements.

## See Also

- [Microsoft.Quantum.Arrays.Zipped3](xref:Microsoft.Quantum.Arrays.Zipped3)
- [Microsoft.Quantum.Arrays.Zipped4](xref:Microsoft.Quantum.Arrays.Zipped4)
- [Microsoft.Quantum.Arrays.Unzipped](xref:Microsoft.Quantum.Arrays.Unzipped)