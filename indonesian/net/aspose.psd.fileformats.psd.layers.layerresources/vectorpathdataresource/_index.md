---
title: "Kelas VectorPathDataResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource kelas. Kelas VectorPathDataResource. Sumber daya ini berisi informasi tentang masker lapisan vektor"
type: docs
weight: 3740
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
{{< psd/tize >}}
## VectorPathDataResource class

Kelas VectorPathDataResource. Sumber daya ini berisi informasi tentang masker lapisan vektor

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini dinonaktifkan. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini terbalik. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tidak terhubung. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Mendapatkan kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Mendapatkan atau mengatur catatan jalur. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Mendapatkan tanda tangan. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Mendapatkan atau mengatur versi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan String yang mewakili instance ini. |

## Contoh

Contoh berikut menunjukkan dukungan pemrosesan Masker Vektor Lapisan. Bagaimana cara kerja penyuntingan jalur dan bagaimana Aspose.PSD menggambar gambar akhir.

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// Membaca
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // Lakukan perubahan pada titik jalur vektor
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // Mengekspor
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat Juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


