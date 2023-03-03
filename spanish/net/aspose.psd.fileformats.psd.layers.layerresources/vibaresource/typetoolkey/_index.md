---
title: VibAResource.TypeToolKey
second_title: Referencia de API de Aspose.PSD para .NET
description: VibAResource campo. La clave de información de la herramienta de tipo.
type: docs
weight: 80
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
## VibAResource.TypeToolKey field

La clave de información de la herramienta de tipo.

```csharp
public const int TypeToolKey;
```

### Ejemplos

El siguiente ejemplo de código demuestra la compatibilidad con el recurso VibAResource.

```csharp
[C#]

// Ejemplo del soporte de lectura y escritura de Vibration Resource en tiempo de ejecución.
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
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* asamblea [Aspose.PSD](../../../)


