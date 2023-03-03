---
title: BlackWhiteAdjustmentLayer.Reds
second_title: Referencia de API de Aspose.PSD para .NET
description: BlackWhiteAdjustmentLayer propiedad. Obtiene o establece el valor de los rojos.
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/reds/
---
## BlackWhiteAdjustmentLayer.Reds property

Obtiene o establece el valor de los rojos.

```csharp
public int Reds { get; set; }
```

### El valor de la propiedad

El valor de los rojos.

### Ejemplos

El siguiente ejemplo demuestra cómo puede agregar la capa de ajuste de blanco y negro en tiempo de ejecución en Aspose.PSD

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

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


