---
title: "ImageAttributes.SetRemapTable"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageAttributes-metod. Ställer in färgremap-tabellen för standardkategorin."
type: docs
weight: 190
url: /sv/net/aspose.psd/imageattributes/setremaptable/
---
{{< psd/tize >}}
## SetRemapTable(ColorMap[]) {#setremaptable}

Ställer in färg-omkartläggningstabellen för standardkategorin.

```csharp
public void SetRemapTable(ColorMap[] map)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | ColorMap[] | En array av färgpar av typen [`ColorMap`](../../colormap/). Varje färgpar innehåller en befintlig färg (det första värdet) och färgen som den kommer att mappas till (det andra värdet). |

### Se även

* class [ColorMap](../../colormap/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetRemapTable(ColorMap[], ColorAdjustType) {#setremaptable_1}

Ställer in färg-omkartläggningstabellen för en angiven kategori.

```csharp
public void SetRemapTable(ColorMap[] map, ColorAdjustType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| map | ColorMap[] | En array av färgpar av typen [`ColorMap`](../../colormap/). Varje färgpar innehåller en befintlig färg (det första värdet) och färgen som den kommer att mappas till (det andra värdet). |
| type | ColorAdjustType | Ett element av [`ColorAdjustType`](../../coloradjusttype/) som specificerar den kategori för vilken färg‑remap‑tabellen är inställd. |

### Se även

* class [ColorMap](../../colormap/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


