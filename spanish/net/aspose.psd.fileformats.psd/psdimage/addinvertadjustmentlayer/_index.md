---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PsdImage. Añade una capa de ajuste de inversión"
type: docs
weight: 380
url: /es/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Añade una capa de ajuste de inversión.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Valor devuelto

La capa de inversión creada

## Ejemplos

El siguiente código muestra el soporte para InvertAdjustmentLayer y cómo agregar InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### Ver también

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


