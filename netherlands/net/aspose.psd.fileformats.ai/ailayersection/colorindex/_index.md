---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "AiLayerSection-eigenschap. Haalt of stelt de index van de kleur. Dit argument kan waarden tussen 1 en 26 aannemen. Elk geheel getal vertegenwoordigt een kleur die aan de laag kan worden toegewezen voor gebruikersidentificatiedoeleinden"
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Haalt of stelt de index van de kleur. Dit argument kan waarden tussen –1 en 26 aannemen. Elk geheel getal vertegenwoordigt een kleur die aan de laag kan worden toegewezen voor gebruikersidentificatiedoeleinden.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

De index van de kleur.

## Voorbeelden

De volgende code demonstreert de ondersteuning van HasMultiLayerMasks- en ColorIndex-eigenschappen in AiLayerSection.

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

### Zie ook

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


