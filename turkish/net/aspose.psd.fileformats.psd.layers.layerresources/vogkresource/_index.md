---
title: "Sınıf VogkResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource sınıfı. Vektör Başlangıç Verisi kaynağı"
type: docs
weight: 3770
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
{{< psd/tize >}}
## VogkResource class

Vektör Başlangıç Verisi kaynağı.

```csharp
public sealed class VogkResource : LayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [VogkResource](vogkresource/)() | `VogkResource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | Şekil köken ayarlarını alır veya ayarlar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, VogkResource kaynağının desteğini gösterir.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Okuma
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Düzenleme
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


