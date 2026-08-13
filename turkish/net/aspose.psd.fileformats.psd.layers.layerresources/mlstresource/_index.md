---
title: "Sınıf MlstResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource sınıfı. mlst kaynağı. Bu sınıf, diğer şeylerin yanı sıra, katmanın zaman çizelgesindeki konumu hakkında bilgi içerir"
type: docs
weight: 3170
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
{{< psd/tize >}}
## MlstResource class

mlst kaynağı. Bu sınıf, diğer şeylerin yanı sıra, katmanın zaman çizelgesindeki konumu hakkında bilgi içerir.

```csharp
public class MlstResource : LayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MlstResource](mlstresource/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Tanımlayıcı sürümünü alır veya ayarlar. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Yapıları alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Belirtilen akış konteynerini kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki kod, katman durumlarını manipüle etmek için düşük seviyeli bir mekanizma sağlayan MlstResource kaynağının desteğini gösterir.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Çerçeve 1'de katman 1'i devre dışı bırak
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


