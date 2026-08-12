---
title: "VibranceLayer.Vibrance"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad VibranceLayer. Obtiene o establece la vibrancia"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Obtiene o establece la vibrancia.

```csharp
public int Vibrance { get; set; }
```

### Property Value

La vibrancia.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | La vibrancia debe estar en el rango de -180 a +180 |

## Ejemplos

El siguiente ejemplo de código demuestra el soporte de la capa VibranceLayer y la capacidad de editar este ajuste.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Creando una nueva VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Ver también

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


