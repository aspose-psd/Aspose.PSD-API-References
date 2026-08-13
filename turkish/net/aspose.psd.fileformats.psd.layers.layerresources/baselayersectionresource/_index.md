---
title: "Sınıf BaseLayerSectionResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseLayerSectionResource sınıfı. Katman bölümü kaynakları için temel sınıf"
type: docs
weight: 2560
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/
---
{{< psd/tize >}}
## BaseLayerSectionResource class

Katman bölümü kaynakları için temel sınıf

```csharp
public abstract class BaseLayerSectionResource : LayerResource
```

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

## Örnekler

Aşağıdaki kod, katman bölümü kaynaklarının sınıf hiyerarşisini gösterir.

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
    AssertAreEqual((psdImage.Layers[3].Resources[3] as LayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[3].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Length, 4);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).BlendModeKey, BlendMode.Absent);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Subtype, LayerSectionSubtype.NotUsed);

    psdImage.Save(outFile);
}

// kaydetme sonrası kontrol et
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[3].Resources[3] as LayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[3].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Length, 4);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).BlendModeKey, BlendMode.Absent);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Subtype, LayerSectionSubtype.NotUsed);
}

File.Delete(outFile);
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


