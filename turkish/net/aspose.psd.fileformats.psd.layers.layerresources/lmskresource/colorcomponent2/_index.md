---
title: "LmskResource.ColorComponent2"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LmskResource özelliği. Renk bileşeni 2'yi alır"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/
---
{{< psd/tize >}}
## LmskResource.ColorComponent2 property

Renk bileşeni 2'yi alır.

```csharp
public ushort ColorComponent2 { get; set; }
```

### Property Value

Renk bileşeni 2.

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

* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


