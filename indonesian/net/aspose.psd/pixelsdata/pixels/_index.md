---
title: PixelsData.Pixels
second_title: Aspose.PSD untuk Referensi .NET API
description: PixelsData Properti. Mendapat atau menyetel data piksel.
type: docs
weight: 30
url: /id/net/aspose.psd/pixelsdata/pixels/
---
## PixelsData.Pixels property

Mendapat atau menyetel data piksel.

```csharp
public int[] Pixels { get; set; }
```

### Contoh

Kode berikut menunjukkan cara membuat filter cerdas kustom yang memiliki perender kustom.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Inisiasi filter pintar 'Crystallize' yang tidak didukung pada larik masukan
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

        // Terapkan filter ke layer mask
        smartFilter.ApplyToMask(maskLayer);

        // Terapkan filter ke lapisan
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
        // dapatkan nilai Ukuran Kristalisasi
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

### Lihat juga

* class [PixelsData](../)
* ruang nama [Aspose.PSD](../../pixelsdata/)
* perakitan [Aspose.PSD](../../../)


