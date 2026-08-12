---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad AiLayerSection. Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer"
type: docs
weight: 60
url: /es/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Obtiene o establece un valor que indica si esta instancia tiene máscaras multilayer.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` si esta instancia tiene máscaras multilayer; de lo contrario, `false`.

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


