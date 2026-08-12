---
title: "VibAResource.PsdVersion"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad de VibAResource. Obtiene la versión PSD"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/
---
{{< psd/tize >}}
## VibAResource.PsdVersion property

Obtiene la versión psd.

```csharp
public override int PsdVersion { get; }
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


