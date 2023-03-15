---
title: Interface ISmartFilterRenderer
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering.ISmartFilterRenderer интерфейс. Интерфейс для конкретного средства визуализации интеллектуальных фильтров.
type: docs
weight: 3450
url: /ru/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/
---
## ISmartFilterRenderer interface

Интерфейс для конкретного средства визуализации интеллектуальных фильтров.

```csharp
public interface ISmartFilterRenderer
```

## Методы

| Имя | Описание |
| --- | --- |
| [Render](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/)(PixelsData) | Визуализирует текущий интеллектуальный фильтр для данных пикселей. |

### Примеры

В следующем коде показано, как создать настраиваемый интеллектуальный фильтр с настраиваемым модулем визуализации.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Инициализирует неподдерживаемый интеллектуальный фильтр «Кристаллизовать» во входном массиве
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // идентификатор смарт-фильтра «Кристаллизовать».
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

        // Применить фильтр к смарт-объекту
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Применяем фильтр к маске слоя
        smartFilter.ApplyToMask(maskLayer);

        //Применяем фильтр к слою
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
        // идентификатор смарт-фильтра «Кристаллизовать».
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // получаем структуру фильтра
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // получить значение размера кристаллизации
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

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* сборка [Aspose.PSD](../../)


