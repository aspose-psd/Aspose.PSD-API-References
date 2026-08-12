---
title: "SoCoResource.Color"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad SoCoResource. Obtiene el color RGB"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

Obtiene el color RGB.

```csharp
public Color Color { get; set; }
```

### Valor devuelto

El color RGB

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

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


