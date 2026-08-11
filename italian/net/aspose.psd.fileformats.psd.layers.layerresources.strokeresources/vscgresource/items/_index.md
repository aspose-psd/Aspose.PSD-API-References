---
title: "VscgResource.Items"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà VscgResource. Ottiene o imposta l'array di elementi di struttura. Attenzione: i valori dell'array Items devono corrispondere alla proprietà KeyForData, che determina il tipo di impostazioni di riempimento memorizzate nelle strutture all'interno di Items"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/
---
{{< psd/tize >}}
## VscgResource.Items property

Ottiene o imposta l'array di elementi della struttura. **Warning:** I valori dell'array `Items` devono corrispondere alla proprietà `KeyForData`, che determina il tipo di impostazioni di riempimento memorizzate nelle strutture all'interno di `Items`.

```csharp
public OSTypeStructure[] Items { get; }
```

### Property Value

L'array di elementi [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/).

## Esempi

Il codice seguente dimostra il supporto di VscgResource.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// verifica delle modifiche
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### Vedi anche

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [VscgResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


