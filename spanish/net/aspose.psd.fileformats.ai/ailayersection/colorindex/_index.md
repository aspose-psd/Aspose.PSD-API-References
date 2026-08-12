---
title: "AiLayerSection.ColorIndex"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad AiLayerSection. Obtiene o establece el índice del color. Este argumento puede tomar valores entre 1 y 26. Cada entero representa un color que puede asignarse a la capa con fines de identificación del usuario"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Obtiene o establece el índice del color. Este argumento puede tomar valores entre –1 y 26. Cada entero representa un color que puede asignarse a la capa para propósitos de identificación del usuario.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

El índice del color.

## Ejemplos

El siguiente código demuestra el soporte de las propiedades HasMultiLayerMasks y ColorIndex en AiLayerSection.

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### Ver también

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


