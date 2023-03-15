---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Referencia de API de Aspose.PSD para .NET
description: PsdImage método. Agrega la capa de ajuste de blanco y negro.
type: docs
weight: 290
url: /es/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Agrega la capa de ajuste de blanco y negro.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Valor_devuelto

La capa de ajuste de blanco y negro creada.

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

### Ver también

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* asamblea [Aspose.PSD](../../../)


