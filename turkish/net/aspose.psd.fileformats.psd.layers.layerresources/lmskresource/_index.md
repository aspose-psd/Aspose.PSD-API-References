---
title: "Sınıf LmskResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource sınıfı. LMsk kaynağı"
type: docs
weight: 3020
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

LMsk kaynağı.

```csharp
public class LmskResource : LayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LmskResource](lmskresource/)() | `LmskResource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Renk bileşeni 1'i alır. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Renk bileşeni 2'yi alır. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Renk bileşeni 3'ü alır. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Renk bileşeni 4'ü alır. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Renk uzayını alır. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Bayrağı alır. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Opaklığı alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Açıklamalar

Bu kaynak, belirli bir renk uzayı türüne işaret eden renk uzayı kimliğini ve 4 renk bileşenini içerir. Kimliğe bağlı olarak renk bileşenlerinin farklı anlamları vardır. Renk uzayı türü dört değer gerektirmiyorsa, ekstra bileşenler tanımsızdır ve her zaman sıfır olarak yazılır. Renk uzayı türlerine göre renk bileşenleri: RGB - ilk üç bileşen kırmızı, yeşil ve mavidir. HSB - ilk üç bileşen renk tonu, doygunluk ve parlaklıktır. CMYK - dört bileşen camgöbeği, macenta, sarı ve siyahtır. Lab - ilk üç bileşen aydınlık, a krominansı ve b krominansıdır. Gri tonlama - ilk bileşen 0...10000 aralığındaki gri değeridir.

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


