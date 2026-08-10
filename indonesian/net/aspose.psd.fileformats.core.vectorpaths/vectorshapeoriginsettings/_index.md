---
title: "Kelas VectorShapeOriginSettings"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeOriginSettings. Pengaturan asal bentuk vektor"
type: docs
weight: 1450
url: /id/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/
---
{{< psd/tize >}}
## VectorShapeOriginSettings class

Pengaturan asal bentuk vektor.

```csharp
public sealed class VectorShapeOriginSettings
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor)() | Menginisialisasi instance baru dari kelas `VectorShapeOriginSettings`. |
| [VectorShapeOriginSettings](vectorshapeoriginsettings/#constructor_1)(bool, int) | Menginisialisasi instance baru dari kelas `VectorShapeOriginSettings`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsOriginBoxCornersPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti sudut kotak asal. |
| [IsOriginIndexPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginindexpresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti origin index. |
| [IsOriginRadiiRectanglePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginradiirectanglepresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti origin radii rectangle. |
| [IsOriginResolutionPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginresolutionpresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti origin resolution. |
| [IsOriginShapeBBoxPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginshapebboxpresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti rectangle. |
| [IsOriginTypePresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isorigintypepresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti origin type. |
| [IsShapeInvalidated](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah shape tidak valid. |
| [IsShapeInvalidatedPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidatedpresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti shape invalidated yang diatur. |
| [IsTransformPresent](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti transform. |
| [OriginBoxCorners](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originboxcorners/) { get; set; } | Mendapatkan atau mengatur sudut kotak origin. |
| [OriginIndex](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/) { get; set; } | Mendapatkan atau mengatur indeks shape origin. |
| [OriginRadiiRectangle](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originradiirectangle/) { get; set; } | Mendapatkan atau mengatur origin radii rectangle. |
| [OriginResolution](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originresolution/) { get; set; } | Mendapatkan atau mengatur origin resolution. |
| [OriginShapeBox](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originshapebox/) { get; set; } | Mendapatkan atau mengatur bounding box shape origin. |
| [OriginType](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/origintype/) { get; set; } | Mendapatkan atau mengatur tipe origin. |
| [Transform](../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/transform/) { get; set; } | Mendapatkan atau mengatur matriks transformasi. |

## Contoh

Contoh berikut menunjukkan dukungan sumber daya VogkResource.

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

    // Membaca
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Menyunting
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


