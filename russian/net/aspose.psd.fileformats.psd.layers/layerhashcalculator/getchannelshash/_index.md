---
title: GetChannelsHash
second_title: Справочник по Aspose.PSD для .NET API
description: Получает хеш каналов.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers/layerhashcalculator/getchannelshash/
---
## LayerHashCalculator.GetChannelsHash method

Получает хеш каналов.

```csharp
public int GetChannelsHash()
```

### Возвращаемое значение

Хэш всех каналов слоя

### Примеры

Следующий код демонстрирует API для получения уникального хэша для похожих слоев в разных файлах.

```csharp
[C#]

/// <summary>
/// Получает имя слоя по.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="image">Изображение.</param>
/// <param name="name">Имя.</param>
/// <возвращает></возвращает>
private static T GetLayerByName<T>(PsdImage image, string name) where T : Layer
{
    var layers = image.Layers;
    foreach (var layer in layers)
    {
        if (layer.Name == name)
        {
            return (T) layer;
        }
    }

    return null;
}

/// <summary>
/// Не равно.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="expected">Ожидаемый.</param>
/// <param name="actual">Фактическое.</param>
/// <exception cref="System.Exception">Аргументы не должны быть равны</exception>
public static void AreNotEqual<T>(T expected, T actual)
{
    if (expected != null && expected.Equals(actual))
    {
        throw new Exception("Arguments must not be equal");
    }
}

/// <summary>
/// Арес равен.
/// </summary>
/// <typeparam name="T"></typeparam>
/// <param name="expected">Ожидаемый.</param>
/// <param name="actual">Фактическое.</param>
/// <exception cref="System.Exception">Аргументы должны быть равны</exception>
public static void AreEqual<T>(T expected, T actual)
{
    if (expected != null && !expected.Equals(actual))
    {
        throw new Exception("Arguments must be equal");
    }
}

/// <summary>
/// Регулирует хэш-тест содержимого слоя.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void RegularLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var layers = new Layer[9];
        var hashers = new LayerHashCalculator[9];

        for (int i = 0; i < layers.Length; i++)
        {
            layers[i] = GetLayerByName<Layer>(im, string.Format("Layer {0}", i + 1));
            hashers[i] = new LayerHashCalculator(layers[i]);
        }

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[1].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreNotEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreNotEqual(hashers[5].GetChannelsHash(), hashers[7].GetChannelsHash());
        AreNotEqual(hashers[0].GetChannelsHash(), hashers[8].GetChannelsHash());

        // Хэши этих слоев равны
        AreEqual(hashers[0].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[4].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[6].GetChannelsHash());

        // Проверяем хэш режима наложения 
        AreEqual(hashers[0].GetBlendingHash(), hashers[3].GetBlendingHash());
        AreEqual(hashers[1].GetBlendingHash(), hashers[4].GetBlendingHash());
        AreNotEqual(hashers[0].GetBlendingHash(), hashers[6].GetBlendingHash());

        // Но указатели разные
        AreNotEqual(layers[0], layers[3]);
        AreNotEqual(layers[1], layers[4]);
        AreNotEqual(layers[0], layers[6]);
    }
}

/// <summary>
/// Заполняет хеш-тест содержимого слоя.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void FillLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var fillLayersNames = new string[] { "Color Fill", "Gradient Fill", "Pattern Fill" };

        var colorFillLayers = new Layer[4];
        var colorFillHashers = new LayerHashCalculator[4];

        for (int fillLayerIndex = 0; fillLayerIndex < fillLayersNames.Length; fillLayerIndex++)
        {
            for (int i = 0; i < 2; i++)
            {
                var index = 0 + i * 2;
                colorFillLayers[index] = GetLayerByName<Layer>(im,
                    string.Format("{0} 1_{1}", fillLayersNames[fillLayerIndex], i + 1));
                colorFillHashers[index] = new LayerHashCalculator(colorFillLayers[index]);
                index = 1 + i * 2;
                colorFillLayers[index] = GetLayerByName<Layer>(im,
                    string.Format("{0} 2_{1}", fillLayersNames[fillLayerIndex], i + 1));
                colorFillHashers[index] = new LayerHashCalculator(colorFillLayers[index]);
            }

            // Похожие слои всегда в одном индексе
            AreEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[2].GetContentHash());
            AreEqual(colorFillHashers[1].GetContentHash(), colorFillHashers[3].GetContentHash());
            AreNotEqual(colorFillHashers[0].GetContentHash(), colorFillHashers[1].GetContentHash());
        }
    }
}

/// <summary>
/// Проверка хеш-теста содержимого слоя объектов.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void SmartObjectLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var smartObjects = new Layer[]
        {
            GetLayerByName<Layer>(im, "Regular1_1"),
            GetLayerByName<Layer>(im, "Regular1_2"),
            GetLayerByName<Layer>(im, "Regular2_1"),
            GetLayerByName<Layer>(im, "Regular2_2"),
            GetLayerByName<Layer>(im, "Smart1_1"),
            GetLayerByName<Layer>(im, "Smart1_2"),
            GetLayerByName<Layer>(im, "Smart2_1"),
            GetLayerByName<Layer>(im, "Smart2_2"),
        };

        var hashers = new LayerHashCalculator[smartObjects.Length];

        for (int i = 0; i < smartObjects.Length; i++)
        {
            hashers[i] = new LayerHashCalculator(smartObjects[i]);
        }

        // Данные канала одинаковы для Layer и Createad из их смарт-объектов.
        AreEqual(hashers[0].GetChannelsHash(), hashers[2].GetChannelsHash());
        AreEqual(hashers[0].GetChannelsHash(), hashers[4].GetChannelsHash());

        // Хэш содержимого отличается, потому что смарт-объект использует другие данные в качестве содержимого
        AreNotEqual(hashers[0].GetContentHash(), hashers[4].GetContentHash());

        // Но смешивание хэша аналогично. Оба слоя — умный и обычный — имеют режим наложения «Нормальный» и непрозрачность 255.
        AreEqual(hashers[0].GetBlendingHash(), hashers[4].GetBlendingHash());

        // Данные канала одинаковы для Layer и Createad из их смарт-объектов.
        AreEqual(hashers[1].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreEqual(hashers[1].GetChannelsHash(), hashers[5].GetChannelsHash());

        // Хэш содержимого отличается, потому что смарт-объект использует другие данные в качестве содержимого
        AreNotEqual(hashers[1].GetContentHash(), hashers[5].GetContentHash());
        // Но смешивание хэша аналогично. Оба слоя — умный и обычный — имеют режим наложения «Нормальный» и непрозрачность 255.
        AreEqual(hashers[1].GetBlendingHash(), hashers[5].GetBlendingHash());

        AreNotEqual(hashers[0].GetChannelsHash(), hashers[1].GetChannelsHash());
        AreNotEqual(hashers[2].GetChannelsHash(), hashers[3].GetChannelsHash());
        AreNotEqual(hashers[4].GetChannelsHash(), hashers[5].GetChannelsHash());
    }
}

/// <summary>
/// Корректировка хеш-теста содержимого слоев.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void AdjustmentLayersContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var adjustments = new Layer[]
        {
            GetLayerByName<Layer>(im, "Brightness/Contrast 1"),
            GetLayerByName<Layer>(im, "Levels 1"),
            GetLayerByName<Layer>(im, "Curves 1"),
            GetLayerByName<Layer>(im, "Exposure 1"),
            GetLayerByName<Layer>(im, "Vibrance 1"),
            GetLayerByName<Layer>(im, "Hue/Saturation 1"),
            GetLayerByName<Layer>(im, "Color Balance 1"),
            GetLayerByName<Layer>(im, "Black & White 1"),
            GetLayerByName<Layer>(im, "Photo Filter 1"),
            GetLayerByName<Layer>(im, "Channel Mixer 1"),
            GetLayerByName<Layer>(im, "Invert 1"),
            GetLayerByName<Layer>(im, "Posterize 1"),
        };

        var length = adjustments.Length;
        var hashers = new LayerHashCalculator[length];

        for (int i = 0; i < length; i++)
        {
            hashers[i] = new LayerHashCalculator(adjustments[i]);
        }

        // Все хеши должны быть разными
        for (int i = 0; i < length; i++)
        {
            for (int j = i + 1; j < length; j++)
            {
                AreNotEqual(hashers[i].GetContentHash(), hashers[j].GetContentHash());
                AreEqual(hashers[i].GetBlendingHash(), hashers[j].GetBlendingHash());
            }
        }
    }
}

/// <summary>
/// Текст хеш-теста содержимого слоев.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void TextLayersContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var textLayers1 = new TextLayer[]
        {
            GetLayerByName<TextLayer>(im, "Text 1"),
            GetLayerByName<TextLayer>(im, "Text 1 Similar"),
            GetLayerByName<TextLayer>(im, "Text 1 Changed"),
        };

        var textLayers2 = new TextLayer[]
        {
            GetLayerByName<TextLayer>(im, "Text 2"),
            GetLayerByName<TextLayer>(im, "Text 2 Similar"),
            GetLayerByName<TextLayer>(im, "Text 2 Changed 1"),
            GetLayerByName<TextLayer>(im, "Text 2 Changed 2"),
            GetLayerByName<TextLayer>(im, "Text 2 Rotated"),
        };

        var textHashers1 = new LayerHashCalculator[textLayers1.Length];
        var textHashers2 = new LayerHashCalculator[textLayers2.Length];

        for (int i = 0; i < textLayers1.Length; i++)
        {
            textHashers1[i] = new LayerHashCalculator(textLayers1[i]);
        }

        for (int i = 0; i < textLayers2.Length; i++)
        {
            textHashers2[i] = new LayerHashCalculator(textLayers2[i]);
        }

        AreEqual(textHashers1[0].GetContentHash(), textHashers1[1].GetContentHash());
        AreNotEqual(textHashers1[0].GetContentHash(), textHashers1[2].GetContentHash());

        AreEqual(textHashers2[0].GetContentHash(), textHashers2[1].GetContentHash());

        AreNotEqual(textHashers2[0].GetContentHash(), textHashers2[2].GetContentHash());
        AreNotEqual(textHashers2[0].GetContentHash(), textHashers2[3].GetContentHash());

        // Матрица преобразования не используется при вычислении хэша. Вы должны дополнительно проверить это
        AreEqual(textHashers2[0].GetContentHash(), textHashers2[4].GetContentHash());

        // В данном случае имеем поворот в матрице
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[4].TransformMatrix);
        // В данном случае у нас есть только перевод (текстовый слой смещен ниже)
        AreNotEqual(textLayers2[0].TransformMatrix, textLayers2[1].TransformMatrix);
    }
}

/// <summary>
/// Группирует хеш-тест содержимого слоя.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void GroupLayerContentHashTest(string fileName)
{
    using (var im = (PsdImage) Image.Load(fileName))
    {
        var fillLayersNames = new string[] { "Color Fill", "Gradient Fill", "Pattern Fill" };

        var groupLayers = new Layer[2];
        var groupLayersHashers = new LayerHashCalculator[2];

        groupLayers[0] = GetLayerByName<Layer>(im, "Fill");
        groupLayers[1] = GetLayerByName<Layer>(im, "Fill copy");

        for (int i = 0; i < groupLayers.Length; i++)
        {
            groupLayersHashers[i] = new LayerHashCalculator(groupLayers[i]);
        }

        // Хэш группового слоя вычисляется из слоев внутри него
        AreEqual(groupLayersHashers[0].GetContentHash(), groupLayersHashers[1].GetContentHash());
        AreNotEqual(groupLayers[0], groupLayers[1]);
    }
}

/// <summary>
/// Регулирует содержимое слоя из разных файлов hash test.
/// </summary>
/// <param name="fileName">Имя файла.</param>
public static void RegularLayerContentFromDifferentFilesHashTest(string fileName, string outputFile)
{
    using (var im = (PsdImage) Image.Load(fileName, new PsdLoadOptions() { ReadOnlyMode = true }))
    {
        im.Save(outputFile);
    }

    using (var im = (PsdImage) Image.Load(fileName))
    {
        using (var imCopied = (PsdImage) Image.Load(outputFile))
        {
            for (int i = 0; i < im.Layers.Length; i++)
            {
                var layer = im.Layers[i];
                var layer_copied = imCopied.Layers[i];
                var hashCalc = new LayerHashCalculator(layer);
                var hashCalc_copied = new LayerHashCalculator(layer_copied);

                // Слои имеют разные указатели
                AreNotEqual(layer, layer_copied);

                // Но хеши слоев равны
                AreEqual(hashCalc.GetChannelsHash(), hashCalc_copied.GetChannelsHash());
                AreEqual(hashCalc.GetContentHash(), hashCalc_copied.GetContentHash());
            }
        }
    }
    
    File.Delete(outputFile);
}
```

### Смотрите также

* class [LayerHashCalculator](../../layerhashcalculator)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layerhashcalculator)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
