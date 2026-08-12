---
title: "Clase SoCoResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource. Clase SoCoResource. Este recurso contiene información sobre capas de relleno de color"
type: docs
weight: 3360
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
{{< psd/tize >}}
## SoCoResource class

Clase SoCoResource. Este recurso contiene información sobre capas de relleno de color

```csharp
public class SoCoResource : FillLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SoCoResource](socoresource/)() | Inicializa una nueva instancia de la clase `SoCoResource`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Obtiene el color RGB. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

## Ejemplos

El siguiente ejemplo muestra cómo editas SoCoResource (Recurso de capa para capa de relleno de color)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Búsqueda de FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Búsqueda de SoCoResource en la lista de recursos de capa
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // Configurando la propiedad Color de SoCoResource
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


