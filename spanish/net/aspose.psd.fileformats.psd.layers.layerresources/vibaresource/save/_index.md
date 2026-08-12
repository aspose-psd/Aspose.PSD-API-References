---
title: "VibAResource.Save"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método de VibAResource. Guarda el recurso en el contenedor de flujo especificado"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

Guarda el recurso en el contenedor de flujo especificado.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | StreamContainer | El contenedor de flujo donde guardar. |
| psdVersion | Int32 | La versión PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


