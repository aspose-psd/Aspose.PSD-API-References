---
title: "Layer.IsVisible"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad Layer. Obtiene o establece un valor que indica si la capa es visible"
type: docs
weight: 180
url: /es/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Obtiene o establece un valor que indica si la capa es visible

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` si esta instancia es visible; de lo contrario, `false`.

## Ejemplos

El siguiente ejemplo muestra cómo puedes cambiar la visibilidad de LayerGroup en Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// realiza cambios en los nombres de las capas y guárdalo
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Desactiva todo dentro de un grupo
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Ver también

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


