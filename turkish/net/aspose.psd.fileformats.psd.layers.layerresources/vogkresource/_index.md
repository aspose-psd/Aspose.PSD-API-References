---
title: Class VogkResource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource sınıf. Vektör Oluşturma Verileri kaynağı.
type: docs
weight: 3370
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

Vektör Oluşturma Verileri kaynağı.

```csharp
public sealed class VogkResource : LayerResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [VogkResource](vogkresource/)() | Yeni bir örneğini başlatır.`VogkResource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/) { get; } | Katman kaynak anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | Katman kaynak uzunluğunu bayt cinsinden alır. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0 kısıtlama olmadığını gösterir. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | Şekil başlangıç ayarlarını alır veya ayarlar. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature/) { get; } | Katman kaynak imzasını alır. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | Sürümü alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış kapsayıcısına kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

### Örnekler

Aşağıdaki örnek, VogkResource kaynağının desteğini göstermektedir.

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

    // düzenleme
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Ayrıca bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* toplantı [Aspose.PSD](../../)


