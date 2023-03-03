---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: Referencia de API de Aspose.PSD para .NET
description: BlackWhiteAdjustmentLayer propiedad. Obtiene o establece el valor de tipo predeterminado en blanco y negro.
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
## BlackWhiteAdjustmentLayer.BwPresetKind property

Obtiene o establece el valor de tipo predeterminado en blanco y negro.

```csharp
public int BwPresetKind { get; set; }
```

### El valor de la propiedad

El valor de tipo predeterminado en blanco y negro.

### Ejemplos

El siguiente ejemplo demuestra cómo puede manipular las propiedades de la capa de ajuste de blanco y negro en Aspose.PSD

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### Ver también

* class [BlackWhiteAdjustmentLayer](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* asamblea [Aspose.PSD](../../../)


