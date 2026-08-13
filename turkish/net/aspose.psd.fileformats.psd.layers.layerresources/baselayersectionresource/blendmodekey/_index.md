---
title: "BaseLayerSectionResource.BlendModeKey"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BaseLayerSectionResource özelliği. Karışım modu anahtarını alır veya ayarlar"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/
---
{{< psd/tize >}}
## BaseLayerSectionResource.BlendModeKey property

Karıştırma modu anahtarını alır veya ayarlar.

```csharp
public BlendMode BlendModeKey { get; set; }
```

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | BlendModeKey uzunluğu 4 karakter olmalıdır. |

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [BaseLayerSectionResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


