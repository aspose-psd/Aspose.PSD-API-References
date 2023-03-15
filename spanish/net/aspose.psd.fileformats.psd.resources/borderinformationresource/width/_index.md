---
title: BorderInformationResource.Width
second_title: Referencia de API de Aspose.PSD para .NET
description: BorderInformationResource propiedad. Obtiene o establece el ancho del borde.
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

Obtiene o establece el ancho del borde.

```csharp
public double Width { get; set; }
```

### Ejemplos

El siguiente ejemplo demuestra la compatibilidad del recurso BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // actualizar BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ver también

* class [BorderInformationResource](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* asamblea [Aspose.PSD](../../../)


