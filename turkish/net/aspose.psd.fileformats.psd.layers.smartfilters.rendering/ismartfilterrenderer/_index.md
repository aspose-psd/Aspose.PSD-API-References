---
title: "Arayüz ISmartFilterRenderer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering.ISmartFilterRenderer arayüzü. Belirli bir akıllı filtre işleyicisi için arayüz."
type: docs
weight: 3880
url: /tr/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/
---
{{< psd/tize >}}
## ISmartFilterRenderer interface

Belirli bir akıllı filtre oluşturucusu için arabirim.

```csharp
public interface ISmartFilterRenderer
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Render](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/)(PixelsData) | Mevcut akıllı filtreyi piksel verileri üzerinde işler. |

## Örnekler

Aşağıdaki kod, özel bir işleyiciye sahip özel bir akıllı filtre nasıl oluşturulacağını gösterir.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Desteklenmeyen 'Crystallize' akıllı filtresini giriş dizisinde başlatır
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' akıllı filtre kimliği.
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

        // Filtreyi SmartObject'e uygula
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Filtreyi katman maskesine uygula
        smartFilter.ApplyToMask(maskLayer);

        //Filtreyi layer'a uygula
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
        // 'Crystallize' akıllı filtre kimliği.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // filtre yapısını al
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Crystallize Size değerini al
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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../)


