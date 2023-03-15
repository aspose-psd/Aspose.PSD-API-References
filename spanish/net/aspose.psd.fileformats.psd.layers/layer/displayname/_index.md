---
title: Layer.DisplayName
second_title: Referencia de API de Aspose.PSD para .NET
description: Layer propiedad. Obtiene o establece el nombre para mostrar de la capa.
type: docs
weight: 100
url: /es/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Obtiene o establece el nombre para mostrar de la capa.

```csharp
public string DisplayName { get; set; }
```

### El valor de la propiedad

El nombre para mostrar de la capa.

### Ejemplos

El siguiente ejemplo demuestra la capacidad de establecer el valor de DisplayName, en el que se muestra correctamente el nombre de la capa.

```csharp
[C#]

// hacer cambios en los nombres de las capas y guardarlos
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // establece un nuevo valor en la propiedad DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Ver también

* class [Layer](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* asamblea [Aspose.PSD](../../../)


