---
title: "VibAResource.Saturation"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "VibAResource property. Obtiene o establece el valor de saturación"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/
---
{{< psd/tize >}}
## VibAResource.Saturation property

Obtiene o establece el valor de saturación

```csharp
public int Saturation { get; set; }
```

## Ejemplos

El siguiente ejemplo de código muestra el soporte del recurso VibAResource.

```csharp
[C#]

// Ejemplo del soporte de lectura y escritura del Recurso de Vibración en tiempo de ejecución.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Ver también

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


