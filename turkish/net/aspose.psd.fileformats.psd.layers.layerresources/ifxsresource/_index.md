---
title: "Sınıf IfxsResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource sınıfı. Ifxs kaynak grup katman efektleri kaynağı"
type: docs
weight: 2840
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ifxs kaynağı (grup katmanı efektleri kaynağı)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [IfxsResource](ifxsresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Tanımlayıcı sürümünü alır. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki kod, IfxsResource desteğini gösterir.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Örnek, efektli 2 grup katmana sahiptir
    // Bir etkili grup katmanı
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Birden fazla etkili grup katmanı
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Etkilerin sayısını alın ve miktarını doğrulayın
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Grup katmanındaki bir etki 'IfxsResource' kaynağında bulunur
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Grup katmanındaki iki veya daha fazla etki 'ImfxResource' kaynağında bulunur
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Birden fazla etkisi olan grup katmanına üçüncü bir gölge ekleyin
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Ayrıca Bakınız

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


