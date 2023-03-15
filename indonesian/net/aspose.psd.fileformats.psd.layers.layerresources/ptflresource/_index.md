---
title: Class PtFlResource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource kelas. Kelas PtFlResource. Berisi Data Layer Isi Pola.
type: docs
weight: 2960
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
## PtFlResource class

Kelas PtFlResource. Berisi Data Layer Isi Pola.

```csharp
public class PtFlResource : FillLayerResource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PtFlResource](ptflresource/)(string, string) | Menginisialisasi instance baru dari`PtFlResource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [sejajar dengan lapisan]. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah instance ini ditautkan dengan layer. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key/) { get; } | Mendapat kunci sumber daya lapisan. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | Mendapatkan panjang sumber daya lapisan dalam byte. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | Mendapat atau menyetel offset. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | Mendapat atau menyetel pengidentifikasi pola. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | Mendapat atau menetapkan nama pola. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion/) { get; } | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | Mendapat atau menyetel skala. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature/) { get; } | Mendapat tanda tangan sumber daya lapisan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | Menyimpan sumber daya ke wadah aliran yang ditentukan. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | Kunci info alat ketik. |

### Contoh

Contoh berikut menunjukkan dukungan pemuatan dan pengeditan sumber daya PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Membaca
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // Mengedit
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Kami tidak memiliki data pola di PattResource, jadi kami dapat menambahkannya.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Lihat juga

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* perakitan [Aspose.PSD](../../)


