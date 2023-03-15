---
title: ISmartFilterRenderer.Render
second_title: Aspose.PSD for .NET API Referansı
description: ISmartFilterRenderer yöntem. Piksel verilerinde geçerli akıllı filtreyi işler.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
## ISmartFilterRenderer.Render method

Piksel verilerinde geçerli akıllı filtreyi işler.

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pixelsData | PixelsData | Piksel verileri. |

### Geri dönüş değeri

İşlenmiş piksel verilerini döndürür.

### Örnekler

Aşağıdaki kod, özel oluşturucuya sahip özel bir akıllı filtrenin nasıl oluşturulacağını gösterir.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Giriş dizisinde desteklenmeyen 'Kristalleştir' akıllı filtresini başlatır
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Kristalleştir' akıllı filtre kimliği.
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

        // SmartObject'e filtre uygula
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Katman maskesine filtre uygula
        smartFilter.ApplyToMask(maskLayer);

        //katmana filtre uygula
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
        // 'Kristalleştir' akıllı filtre kimliği.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // filtre yapısını al
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Kristalize Boyutun değerini al
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

### Ayrıca bakınız

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../ismartfilterrenderer/)
* toplantı [Aspose.PSD](../../../)


