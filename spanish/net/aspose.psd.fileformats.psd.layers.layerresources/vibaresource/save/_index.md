---
title: VibAResource.Save
second_title: Referencia de API de Aspose.PSD para .NET
description: VibAResource método. Guarda el recurso en el contenedor de flujo especificado.
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

Guarda el recurso en el contenedor de flujo especificado.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| streamContainer | StreamContainer | El contenedor de secuencias en el que guardar. |
| psdVersion | Int32 | La versión PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* asamblea [Aspose.PSD](../../../)


