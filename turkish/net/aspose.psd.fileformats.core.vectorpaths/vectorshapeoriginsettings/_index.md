---
title: "Sınıf VectorShapeOriginSettings"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings sınıfı. Vektör şekil başlangıç ayarları"
type: docs
weight: 1450
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

Vektör şeklinin oluşum ayarları.

```csharp
public sealed class VectorShapeOriginSettings
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | `VectorShapeOriginSettings` sınıfının yeni bir örneğini başlatır. |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | `VectorShapeOriginSettings` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Bu örneğin orijin kutusu köşeleri özelliğine sahip olup olmadığını gösteren bir değeri alır. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Bu örneğin origin index özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Bu örneğin origin radii rectangle özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Bu örneğin origin resolution özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Bu örneğin rectangle özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Bu örneğin origin type özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Şeklin geçersiz olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Bu örneğin shape invalidated özelliği ayarına sahip olup olmadığını gösteren bir değer alır. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Bu örneğin transform özelliğine sahip olup olmadığını gösteren bir değer alır. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | origin box köşelerini alır veya ayarlar. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | origin shape indeksini alır veya ayarlar. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | origin radii rectangle'ı alır veya ayarlar. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | origin resolution'ı alır veya ayarlar. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | origin shape sınırlayıcı kutusunu alır veya ayarlar. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | origin tipini alır veya ayarlar. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | dönüşüm matrisini alır veya ayarlar. |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


