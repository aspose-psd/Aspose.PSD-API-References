---
title: Class GaussianBlurSmartFilter
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.GaussianBlurSmartFilter сорт. Интеллектуальный фильтр GaussianBlur.
type: docs
weight: 3430
url: /ru/net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---
## GaussianBlurSmartFilter class

Интеллектуальный фильтр GaussianBlur.

```csharp
public sealed class GaussianBlurSmartFilter : SmartFilter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GaussianBlurSmartFilter](gaussianblursmartfilter/)() | Инициализирует новый экземпляр`GaussianBlurSmartFilter` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Получает или задает режим наложения. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filterid/) { get; } | Получает идентификатор типа интеллектуального фильтра. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Получает или задает состояние включения интеллектуального фильтра. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/name/) { get; } | Получает имя смарт-фильтра. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Получает или задает значение непрозрачности интеллектуального фильтра. |
| [Radius](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/radius/) { get; set; } | Получает или задает радиус интеллектуального фильтра Гаусса. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Структура исходного дескриптора с данными интеллектуального фильтра. |

## Методы

| Имя | Описание |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Применяет текущий фильтр ко входу[`RasterImage`](../../aspose.psd/rasterimage/) изображение. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Применяет текущий фильтр ко входу[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) данные маски. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Создает почленный клон текущего экземпляра типа. |

## Поля

| Имя | Описание |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filtertype/) | Идентификатор текущего смарт-фильтра. |

### Примеры

Этот пример демонстрирует поддержку интерфейса интеллектуальных фильтров.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // редактируем умные фильтры
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // проверить значения фильтра
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // обновить значения фильтра
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // добавить новые элементы фильтра
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // применить изменения
    smartObj.SmartFilters.UpdateResourceValues();

    // Применение фильтров
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // проверить значения фильтра
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Смотрите также

* class [SmartFilter](../smartfilter/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* сборка [Aspose.PSD](../../)


