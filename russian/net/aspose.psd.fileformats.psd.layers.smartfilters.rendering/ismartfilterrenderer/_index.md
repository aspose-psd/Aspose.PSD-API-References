---
title: "Интерфейс ISmartFilterRenderer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Интерфейс Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering.ISmartFilterRenderer. Интерфейс для конкретного рендерера умного фильтра"
type: docs
weight: 3860
url: /ru/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/
---
{{< psd/tize >}}
## ISmartFilterRenderer interface

Интерфейс для конкретного рендерера умного фильтра.

```csharp
public interface ISmartFilterRenderer
```

## Методы

| Имя | Описание |
| --- | --- |
| [Render](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/)(PixelsData) | Отрисовывает текущий умный фильтр на данных пикселей. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../)


