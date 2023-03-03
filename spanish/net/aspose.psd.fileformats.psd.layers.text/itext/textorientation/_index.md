---
title: IText.TextOrientation
second_title: Referencia de API de Aspose.PSD para .NET
description: IText propiedad. Obtiene o establece la orientación del texto.
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Obtiene o establece la orientación del texto.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### El valor de la propiedad

La orientación del texto.

### Ejemplos

El siguiente código demuestra la capacidad de editar la nueva propiedad TextOrientation. Esto no afecta el renderizado en este momento, pero solo le permite editar el valor de la propiedad.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* asamblea [Aspose.PSD](../../../)


