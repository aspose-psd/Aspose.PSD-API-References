---
title: "Sınıf ArtBResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ArtBResource sınıfı. Kaynaklar için Artboard bilgi verisi."
type: docs
weight: 2520
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---
{{< psd/tize >}}
## ArtBResource class

[`Resources`](../../aspose.psd.fileformats.psd.layers/layer/resources/) için Artboard bilgi verisi.

```csharp
public sealed class ArtBResource : BaseArtboardInfoResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ArtBResource](artbresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArtboardBackgroundType](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/artboardbackgroundtype/) { get; set; } | [`ArtboardBackgroundType`](./artboardbackgroundtype/) alır veya ayarlar |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/color/) { get; set; } | [`Color`](./color/) alır veya ayarlar |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/items/) { get; set; } | [`OSTypeStructure`](../ostypestructure/) öğelerini alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/length/) { get; } |  |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/artbresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki kod, Artboard kaynaklarının desteğini gösterir.

```csharp
[C#]

string srcFile = "artboard1.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtDResource artDResource = (ArtDResource)psdImage.GlobalLayerResources[2];

    ArtBResource artBResource1 = (ArtBResource)psdImage.Layers[2].Resources[7];
    ArtBResource artBResource2 = (ArtBResource)psdImage.Layers[5].Resources[7];

    LyvrResource lyvrResource1 = (LyvrResource)psdImage.Layers[2].Resources[9];
    LyvrResource lyvrResource2 = (LyvrResource)psdImage.Layers[5].Resources[9];

    var countStruct = (IntegerStructure)artDResource.Items[0];
    AssertAreEqual(2, countStruct.Value);

    var presetNameStruct1 = (StringStructure)artBResource1.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct1.Value);

    var presetNameStruct2 = (StringStructure)artBResource2.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct2.Value);

    AssertAreEqual(160, lyvrResource1.Version);
    AssertAreEqual(160, lyvrResource2.Version);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}
```

### Ayrıca Bakınız

* class [BaseArtboardInfoResource](../baseartboardinforesource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


