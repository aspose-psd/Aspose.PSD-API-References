---
title: "Enum ColorSpace"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. Renk uzayı türleri"
type: docs
weight: 4190
url: /tr/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

Renk uzayı türleri.

```csharp
public enum ColorSpace : ushort
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| RGB | `0` | RGB renk uzayı. |
| HSB | `1` | HSB renk uzayı. |
| CMYK | `2` | CMYK renk uzayı. |
| Lab | `7` | Lab renk uzayı. |
| GrayScale | `8` | Gri ölçek renk uzayı. |

## Örnekler

Aşağıdaki kod, LmskResource özelliklerini değiştirerek 16-bit görüntülerde Katman Maskesi Görüntüleme Seçeneklerini nasıl değiştireceğinizi gösterir.

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

// 16-bit görüntüyü yükle.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // LmskResource'ı bul.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // LmskResource özelliklerini kontrol et.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // LmskResource özelliklerini değiştir.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Görüntüyü kaydet.
    image.Save(outputPsd);
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


