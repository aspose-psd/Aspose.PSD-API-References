---
title: "Enumeración TextOrientation"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation enum. Enumeración para el modo de orientación del texto."
type: docs
weight: 4480
url: /es/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Enumeración para el modo de orientación del texto.

```csharp
public enum TextOrientation
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Horizontal | `0` | La orientación de texto horizontal. |
| Vertical | `2` | La orientación de texto vertical. |

## Ejemplos

El siguiente código demuestra la capacidad de editar la nueva propiedad TextOrientation. Esto no afecta la renderización en este momento, pero solo permite editar el valor de la propiedad.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Lectura correcta
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Lectura correcta
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


