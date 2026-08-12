---
title: "PsdImage.AddBlackWhiteAdjustmentLayer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PsdImage. Añade la capa de ajuste blanco y negro"
type: docs
weight: 300
url: /es/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddBlackWhiteAdjustmentLayer method

Añade la capa de ajuste blanco y negro.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Valor devuelto

La capa de ajuste blanco y negro creada.

## Ejemplos

El siguiente ejemplo muestra cómo puede agregar la capa de ajuste black white en tiempo de ejecución en Aspose.PSD.

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
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


