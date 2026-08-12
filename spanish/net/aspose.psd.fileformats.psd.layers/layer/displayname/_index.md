---
title: "Layer.DisplayName"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad Layer. Obtiene o establece el nombre para mostrar de la capa"
type: docs
weight: 110
url: /es/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Obtiene o establece el nombre para mostrar de la capa.

```csharp
public string DisplayName { get; set; }
```

### Property Value

El nombre para mostrar de la capa.

## Ejemplos

El siguiente ejemplo demuestra la capacidad de establecer el valor DisplayName, en el que el nombre de la capa se muestra correctamente.

```csharp
[C#]

// realiza cambios en los nombres de las capas y guárdalo
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // establecer un nuevo valor en la propiedad DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Ver también

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


