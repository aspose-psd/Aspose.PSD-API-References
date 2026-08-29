---
title: "SmartObjectLayer.ExportContents"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод SmartObjectLayer. Экспортирует встроенное или связанное содержимое в файл."
type: docs
weight: 120
url: /ru/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/
---
{{< psd/tize >}}
## SmartObjectLayer.ExportContents method

Экспортирует встроенное или связанное содержимое в файл.

```csharp
public void ExportContents(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к экспортируемому файлу. |

## Примеры

Следующий код демонстрирует поддержку встроенных смарт‑объектов.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Этот пример демонстрирует, как изменить слой смарт‑объекта в файле PSD и экспортировать/обновлять оригинальное встроенное содержимое смарт‑объекта.
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

        // Давайте экспортируем встроенное изображение смарт‑объекта из слоя смарт‑объекта PSD
        smartObjectLayer.ExportContents(exportPath);

        // Давайте проверим, правильно ли сохранено оригинальное изображение
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Давайте инвертируем оригинальное изображение смарт‑объекта
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Давайте заменим встроенное изображение смарт‑объекта в слое PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Давайте проверим, правильно ли сохранено обновлённое изображение
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### См. также

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


