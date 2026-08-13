---
title: "Sınıf LsdkResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LsdkResource class. lsdk katman kaynağı iç içe katman bölüm kaynağı"
type: docs
weight: 3110
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lsdkresource/
---
{{< psd/tize >}}
## LsdkResource class

lsdk katman kaynağı (iç içe katman bölümü kaynağı).

```csharp
public class LsdkResource : BaseLayerSectionResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LsdkResource](lsdkresource/)() | Yeni bir `LsdkResource` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendModeKey](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/) { get; set; } | Karıştırma modu anahtarını alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| [SectionType](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/sectiontype/) { get; set; } | Bölüm tipini alır veya ayarlar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [Subtype](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/subtype/) { get; set; } | Alt tipi alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lsdkresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki kod, LsdkResource desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string srcFile = "123 1.psd";
string outFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
    psdImage.Save(outFile);
}

// kaydetme sonrası kontrol et
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
}
```

### Ayrıca Bakınız

* class [BaseLayerSectionResource](../baselayersectionresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


