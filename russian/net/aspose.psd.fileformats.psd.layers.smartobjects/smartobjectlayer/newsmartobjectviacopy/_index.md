---
title: "SmartObjectLayer.NewSmartObjectViaCopy"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод SmartObjectLayer. Создаёт новый слой смарт‑объекта, копируя текущий. Воспроизводит функцию Layer  Smart Objects  New Smart Object via Copy в Adobe Photoshop. Обратите внимание, что она доступна только для встроенных смарт‑объектов, поскольку встроенное изображение также копируется. Если вы хотите использовать общее встроенное изображение, используйте метод DuplicateLayer method."
type: docs
weight: 140
url: /ru/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectLayer.NewSmartObjectViaCopy method

Создаёт новый слой смарт‑объекта, копируя текущий. Воспроизводит функцию `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` в Adobe Photoshop. Обратите внимание, что она доступна только для встроенных смарт‑объектов, поскольку встроенное изображение также копируется. Если вы хотите использовать общее встроенное изображение, используйте метод [`DuplicateLayer`](../duplicatelayer/) method.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### Возвращаемое значение

Клонированный экземпляр [`SmartObjectLayer`](../).

## Примеры

Эти примеры демонстрируют, как копировать слои смарт‑объектов в PSD‑изображении.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Эти примеры демонстрируют, как копировать слои смарт‑объектов в PSD‑изображении.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // Давайте инвертируем изображение встроенного смарт‑объекта (для вложенного PSD‑изображения инвертируем только его первый слой).
            InvertImage(innerImage);

            // Давайте заменим встроенное изображение смарт‑объекта в слое PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Дублированный слой использует то же встроенное изображение, что и оригинальный смарт‑объект.
        // и его необходимо явно обновлять, иначе кэш рендеринга останется неизменным.
        // Мы обновляем каждый смарт‑объект, чтобы убедиться, что новый слой, созданный методом NewSmartObjectViaCopy
        // не использует общее встроенное изображение с другими.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Инвертирует растровое изображение, включая PSD‑изображение.
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// Инвертирует растровое изображение.
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### См. также

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


