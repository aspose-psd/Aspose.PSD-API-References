---
title: "PixelsData.Bounds"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PixelsData. Получает или задает границы данных пикселей"
type: docs
weight: 20
url: /ru/net/aspose.psd/pixelsdata/bounds/
---
{{< psd/tize >}}
## PixelsData.Bounds property

Получает или задает границы данных пикселей.

```csharp
public Rectangle Bounds { get; set; }
```

## Примеры

Следующий код показывает, как создать пользовательский умный фильтр с пользовательским рендерером.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Инициализирует неподдерживаемый умный фильтр 'Crystallize' в входном массиве
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // ID умного фильтра 'Crystallize'.
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

        // Применить фильтр к SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Применить фильтр к маске слоя
        smartFilter.ApplyToMask(maskLayer);

        //Применить фильтр к слою
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
        // ID умного фильтра 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // получить структуру фильтра
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // получить значение размера Crystallize
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

### См. также

* struct [Rectangle](../../rectangle/)
* class [PixelsData](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


