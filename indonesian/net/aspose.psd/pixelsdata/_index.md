---
title: "Kelas PixelsData"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.PixelsData. Kelas untuk menyimpan data piksel gambar dan batasnya"
type: docs
weight: 5740
url: /id/net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

Kelas untuk menyimpan data piksel gambar dan batasnya.

```csharp
public sealed class PixelsData : ICloneable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `PixelsData`. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | Menginisialisasi sebuah instance baru dari kelas `PixelsData`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | Mendapatkan atau mengatur batas data piksel. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | Mendapatkan atau mengatur data piksel. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../aspose.psd/pixelsdata/clone/)() | Ini membuat salinan penuh dari instance. |

## Contoh

Kode berikut menunjukkan cara membuat filter pintar khusus yang memiliki renderer khusus.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Menginisialisasi filter pintar 'Crystallize' yang tidak didukung pada array input
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // ID filter pintar 'Crystallize'.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // Terapkan filter ke SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Terapkan filter ke masker lapisan
        smartFilter.ApplyToMask(maskLayer);

        //Terapkan filter ke lapisan
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // ID filter pintar 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // dapatkan struktur filter
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // dapatkan nilai Ukuran Crystallize
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


