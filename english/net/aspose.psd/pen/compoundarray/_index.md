---
title: CompoundArray
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 50
url: /net/aspose.psd/pen/compoundarray/
---
## Pen.CompoundArray property

Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces.

```csharp
public float[] CompoundArray { get; set; }
```

## Property Value

An array of real numbers that specifies the compound array. The elements in the array must be in increasing order, not less than 0, and not greater than 1.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | The `CompoundArray` property is set on an immutable [`Pen`](../../pen), such as those returned by the [`Pen`](../../pen) class. |

### See Also

* class [Pen](../../pen)
* namespace [Aspose.PSD](../../pen)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
