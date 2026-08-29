---
title: "LmskResource.Opacity"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà LmskResource. Ottiene l'opacità"
type: docs
weight: 90
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/
---
{{< psd/tize >}}
## LmskResource.Opacity property

Ottiene l'opacità.

```csharp
public short Opacity { get; set; }
```

### Property Value

L'opacità.

## Esempi

Il codice seguente dimostra come modificare le Opzioni di visualizzazione della Maschera di livello su immagini a 16 bit modificando le proprietà di LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Carica immagine a 16 bit.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Trova LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Verifica le proprietà di LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Modifica le proprietà di LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Salva l'immagine.
    image.Save(outputPsd);
}
```

### Vedi anche

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


