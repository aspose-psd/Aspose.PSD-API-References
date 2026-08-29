---
title: "SmartObjectLayer.ContentType"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство SmartObjectLayer. Возвращает тип содержимого слоя смарт-объекта. Содержимое встроенного смарт-объекта представляет собой встроенный необработанный файл изображения Data. Содержимое связанного смарт-объекта — это необработанное содержимое связанного файла изображения, если доступен LiFeDataSource. Мы не поддерживаем загрузку из Adobe Photoshop Graphics Library, когда IsLibraryLink истинно. Для обычных файлов‑ссылок сначала используется RelativePath для поиска файла относительно пути исходного изображения SourceImagePath; если он недоступен, ищем в FullPath; если и это не удалось, ищем файл‑ссылку в том же каталоге, где находится наше изображение SourceImagePath."
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/
---
{{< psd/tize >}}
## SmartObjectLayer.ContentType property

Возвращает тип содержимого слоя смарт-объекта. Содержимое встроенного смарт-объекта — это встроенный необработанный файл изображения: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/). Содержимое связанного смарт-объекта — это необработанное содержимое связанного файла изображения, если доступно: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Мы не поддерживаем загрузку из Adobe Photoshop Graphics Library, когда [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) истинно. Для обычных файлов‑ссылок сначала используем [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) для поиска файла относительно пути исходного изображения SourceImagePath; если он недоступен, ищем в [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/); если и это не удалось, ищем файл‑ссылку в том же каталоге, где находится наше изображение: SourceImagePath.

```csharp
public SmartObjectType ContentType { get; }
```

### Property Value

Тип содержимого слоя смарт-объекта.

## Примеры

Следующий код демонстрирует поддержку обновления связанных смарт‑объектов.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// В этом примере показано, как обновить внешний или встроенный слой смарт‑объекта, используя эти методы:
// RelinkToFile, UpdateModifiedContent, ExportContents
ExampleOfUpdatingSmartObjectLayer("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfUpdatingSmartObjectLayer("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfUpdatingSmartObjectLayer(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // В этом примере показано, как изменить слой смарт‑объекта в файле PSD и экспортировать/обновить его содержимое.
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "updating_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_modified.png";
    string png2OutputPath = dataDir + fileName + "_updated_modified.png";
    string psd2OutputPath = dataDir + fileName + "_updated_modified.psd";
    string exportPath = dataDir + fileName + "_exported." + GetFormatExt(format);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        var contentType = smartObjectLayer.ContentType;
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        if (contentType == SmartObjectType.AvailableLinked)
        {
            Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
            // Экспортируем внешнее изображение смарт‑объекта из слоя смарт‑объекта PSD в новое место
            // потому что мы собираемся его изменить.
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // Инвертируем содержимое смарт‑объекта: внутреннее (не кэшированное) изображение
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // Проверим, не влияет ли изменённое содержимое на рендеринг пока.
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // Проверим, влияет ли обновлённое содержимое на рендеринг и сохраняется ли изображение PSD корректно
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// В этом примере показано, как преобразовать встроенный смарт‑объект во внешнее связанное содержимое с помощью метода ConvertToLinked.
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("new_panama-papers-4.psd", 0x10caa, 0, 0, 0x280, 0x169, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r3-embedded.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-tiff.psd", 0xca94, 0, 0, 0xb, 0x10, FileFormat.Tiff);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-bmp.psd", 0x278, 0, 0, 0xb, 0x10, FileFormat.Bmp);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-gif.psd", 0x3ec, 0, 0, 0xb, 0x10, FileFormat.Gif);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg.psd", 0x327, 0, 0, 0xb, 0x10, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg2000.psd", 0x519f, 0, 0, 0xb, 0x10, FileFormat.Jpeg2000);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-psd.psd", 0xc074, 0, 0, 0xb, 0x10, FileFormat.Psd);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfEmbeddedSmartObjectLayerToLinkedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // Это демонстрирует, как преобразовать встроенный слой смарт‑объекта в файле PSD во внешний.
    var formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_linked_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_external.png";
    string psdOutputPath = dataDir + fileName + "_to_external.psd";
    string externalPath = dataDir + fileName + "_external." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        Directory.CreateDirectory(Path.GetDirectoryName(externalPath));
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer.ConvertToLinked(externalPath);

        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        // Проверим, сохраняется ли преобразованное изображение корректно
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);
    }
}

// В этом примере показано, как встроить один внешний слой смарт‑объекта или все связанные слои в файл PSD с помощью метода EmbedLinked.
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
void ExampleOfLinkedSmartObjectLayerToEmbeddedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_embedded_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_embedded.png";
    string psdOutputPath = dataDir + fileName + "_to_embedded.psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer0 = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer0.EmbedLinked();
        AssertAreEqual(contentsLength, smartObjectLayer0.Contents.Length);
        AssertAreEqual(left, smartObjectLayer0.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer0.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer0.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer0.ContentsBounds.Bottom);
        if (image.Layers.Length >= 2)
        {
            var smartObjectLayer1 = (SmartObjectLayer)image.Layers[1];
            AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer0.ContentType);
            AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer1.ContentType);

            image.SmartObjectProvider.EmbedAllLinked();
            foreach (Layer layer in image.Layers)
            {
                var smartLayer = layer as SmartObjectLayer;
                if (smartLayer != null)
                {
                    AssertAreEqual(SmartObjectType.Embedded, smartLayer.ContentType);
                }
            }
        }

        Directory.CreateDirectory(Path.GetDirectoryName(psdOutputPath));
        // Проверим, сохраняется ли преобразованное изображение корректно
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer.ContentType);
    }
}

// В этом примере показано, как изменить внешний слой смарт‑объекта Adobe® Photoshop® и экспортировать/обновить его содержимое
// используя методы ExportContents и ReplaceContents.
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked2.psd", 0x4aea, 0, 0, 10, 10, FileFormat.Psd);
void ExampleOfExternalSmartObjectLayerSupport(string filePath, int contentsLength, int left, int top, int right, int bottom, FileFormat format)
{
    string formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "external_support_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + ".png";
    string psdOutputPath = dataDir + fileName + ".psd";
    string linkOutputPath = dataDir + fileName + "_inverted." + formatExt;
    string png2OutputPath = dataDir + fileName + "_updated.png";
    string psd2OutputPath = dataDir + fileName + "_updated.psd";
    string exportPath = dataDir + fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[image.Layers.Length - 1];
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
        // Экспортируем связанное изображение смарт‑объекта из слоя смарт‑объекта PSD
        smartObjectLayer.ExportContents(exportPath);

        // Проверим, сохраняется ли оригинальное изображение корректно
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Инвертируем связанное изображение смарт‑объекта
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // Заменим связанное изображение смарт‑объекта в слое PSD
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // Давайте проверим, правильно ли сохранено обновлённое изображение
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Инвертирует изображение.
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

// Получает расширение формата.
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### См. также

* enum [SmartObjectType](../../smartobjecttype/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


