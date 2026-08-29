---
title: "ImageAttributes.SetThreshold"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageAttributes-metod. Ställer in tröskelns genomskinlighetsintervall för standardkategorin."
type: docs
weight: 200
url: /sv/net/aspose.psd/imageattributes/setthreshold/
---
{{< psd/tize >}}
## SetThreshold(float) {#setthreshold}

Ställer in tröskelvärdet (transparentintervall) för standardkategorin.

```csharp
public void SetThreshold(float threshold)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tröskel | Single | Ett reellt tal som specificerar tröskelvärdet. |

### Se även

* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetThreshold(float, ColorAdjustType) {#setthreshold_1}

Ställer in tröskelvärdet (transparentintervall) för en angiven kategori.

```csharp
public void SetThreshold(float threshold, ColorAdjustType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tröskel | Single | Ett tröskelvärde från 0,0 till 1,0 som används som brytpunkt för att sortera färger som kommer att mappas till antingen ett maximalt eller ett minimalt värde. |
| type | ColorAdjustType | Ett element av [`ColorAdjustType`](../../coloradjusttype/) som specificerar den kategori för vilken färgtröskeln är inställd. |

### Se även

* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


