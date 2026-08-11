---
title: "Enum ColorSpace"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. I tipi di spazio colore"
type: docs
weight: 4160
url: /it/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

I tipi di spazio colore.

```csharp
public enum ColorSpace : ushort
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RGB | `0` | Lo spazio colore RGB. |
| HSB | `1` | Lo spazio colore HSB. |
| CMYK | `2` | Lo spazio colore CMYK. |
| Lab | `7` | Lo spazio colore Lab. |
| GrayScale | `8` | Lo spazio colore GrayScale. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


