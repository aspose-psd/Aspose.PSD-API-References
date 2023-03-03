---
title: Layer.IsVisible
second_title: Referencia de API de Aspose.PSD para .NET
description: Layer propiedad. Obtiene o establece un valor que indica si la capa es visible
type: docs
weight: 170
url: /es/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Obtiene o establece un valor que indica si la capa es visible

```csharp
public bool IsVisible { get; set; }
```

### El valor de la propiedad

`verdadero` si esta instancia es visible; de lo contrario,`FALSO` .

### Ejemplos

El siguiente ejemplo demuestra cómo puede cambiar la visibilidad de LayerGroup en Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// hacer cambios en los nombres de las capas y guardarlos
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Apaga todo dentro de un grupo
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
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* asamblea [Aspose.PSD](../../../)


