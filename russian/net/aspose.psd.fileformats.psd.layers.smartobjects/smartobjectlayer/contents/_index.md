---
title: SmartObjectLayer.Contents
second_title: Справочник по Aspose.PSD для .NET API
description: SmartObjectLayer свойство. Получает или задает содержимое слоя смартобъекта. Содержимое встроенного смартобъекта представляет собой встроенный файл необработанного изображенияData и его свойства. Содержимое связанного смартобъекта  это необработанное содержимое связанного файла изображения если оно доступно и его свойстваLiFeDataSource . Мы не поддерживаем загрузку из графической библиотеки Adobe Photoshop  приIsLibraryLink верно. Для обычных файлов ссылок сначала используетсяRelativePath искать файл относительно пути к исходному изображениюSourceImagePath  если нет в наличии смотримFullPath  если нет то ищем файл ссылки в той же директории где наш образSourceImagePath .
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Получает или задает содержимое слоя смарт-объекта. Содержимое встроенного смарт-объекта представляет собой встроенный файл необработанного изображения:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) и его свойства. Содержимое связанного смарт-объекта — это необработанное содержимое связанного файла изображения, если оно доступно, и его свойства:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Мы не поддерживаем загрузку из графической библиотеки Adobe� Photoshop� � при[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) верно. Для обычных файлов ссылок сначала используется[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) искать файл относительно пути к исходному изображениюSourceImagePath , если нет в наличии смотрим[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , если нет то ищем файл ссылки в той же директории где наш образ:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Стоимость имущества

byte[] содержимое слоя смарт-объекта.

### Исключения

| исключение | условие |
| --- | --- |
| NotSupportedException | Не удается получить содержимое из библиотеки Adobe� Photoshop� ��. |

### Примеры

Следующий код демонстрирует поддержку встроенных смарт-объектов.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// В этом примере показано, как изменить слой смарт-объекта в PSD-файле и экспортировать/обновить исходное встроенное содержимое смарт-объекта.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Давайте экспортируем встроенное изображение смарт-объекта из слоя смарт-объекта PSD
        smartObjectLayer.ExportContents(exportPath);

        // Проверяем, правильно ли сохранено исходное изображение
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Давайте инвертируем исходное изображение смарт-объекта
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Давайте заменим встроенное изображение смарт-объекта в слое PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Проверяем, корректно ли сохранено обновленное изображение
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Смотрите также

* class [SmartObjectLayer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* сборка [Aspose.PSD](../../../)


