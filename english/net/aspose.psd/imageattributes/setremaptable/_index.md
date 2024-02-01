---
title: ImageAttributes.SetRemapTable
second_title: Aspose.PSD for .NET API Reference
description: ImageAttributes method. Sets the colorremap table for the default category
type: docs
weight: 190
url: /net/aspose.psd/imageattributes/setremaptable/
---
{{< psd/tize >}}
## SetRemapTable(ColorMap[]) {#setremaptable}

Sets the color-remap table for the default category.

```csharp
public void SetRemapTable(ColorMap[] map)
```

| Parameter | Type | Description |
| --- | --- | --- |
| map | ColorMap[] | An array of color pairs of type [`ColorMap`](../../colormap/). Each color pair contains an existing color (the first value) and the color that it will be mapped to (the second value). |

### See Also

* class [ColorMap](../../colormap/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetRemapTable(ColorMap[], ColorAdjustType) {#setremaptable_1}

Sets the color-remap table for a specified category.

```csharp
public void SetRemapTable(ColorMap[] map, ColorAdjustType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| map | ColorMap[] | An array of color pairs of type [`ColorMap`](../../colormap/). Each color pair contains an existing color (the first value) and the color that it will be mapped to (the second value). |
| type | ColorAdjustType | An element of [`ColorAdjustType`](../../coloradjusttype/) that specifies the category for which the color-remap table is set. |

### See Also

* class [ColorMap](../../colormap/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


