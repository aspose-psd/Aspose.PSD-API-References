---
title: Class VectorShapeOriginSettings
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings sınıf. Vektör şekli oluşturma ayarları.
type: docs
weight: 1440
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
## VectorShapeOriginSettings class

Vektör şekli oluşturma ayarları.

```csharp
public sealed class VectorShapeOriginSettings
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Yeni bir örneğini başlatır.`VectorShapeOriginSettings` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Bu örneğin kaynak kutu köşeleri özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Bu örneğin kaynak dizin özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Bu örneğin, orijin yarıçapı dikdörtgen özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Bu örneğin kaynak çözümleme özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Bu örneğin dikdörtgen özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Bu örneğin kaynak tipi özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Şeklin geçersiz olup olmadığını gösteren bir değer alır veya ayarlar. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Bu örneğin geçersiz kılınan bir özellik setine sahip olup olmadığını gösteren bir değer alır. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Bu örneğin transform özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Başlangıç kutusu köşelerini alır veya ayarlar. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Başlangıç şekli indeksini alır veya ayarlar. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Başlangıç yarıçapı dikdörtgenini alır veya ayarlar. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Başlangıç çözünürlüğünü alır veya ayarlar. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Başlangıç şekli sınırlama kutusunu alır veya ayarlar. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Kaynağın türünü alır veya ayarlar. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Dönüşüm matrisini alır veya ayarlar. |

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

* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* toplantı [Aspose.PSD](../../)


