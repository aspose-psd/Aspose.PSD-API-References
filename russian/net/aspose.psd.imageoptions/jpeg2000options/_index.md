---
title: "Класс Jpeg2000Options"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ImageOptions.Jpeg2000Options. Параметры формата файла Jpeg2000"
type: docs
weight: 5320
url: /ru/net/aspose.psd.imageoptions/jpeg2000options/
---
{{< psd/tize >}}
## Jpeg2000Options class

Параметры формата файла Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Инициализирует новый экземпляр класса `Jpeg2000Options`. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Инициализирует новый экземпляр класса `Jpeg2000Options`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | Получает или задает кодек JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Получает или задает маркеры комментариев Jpeg. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Получает или задает массив коэффициентов сжатия. Разные коэффициенты сжатия для последовательных слоёв. Указанный коэффициент для каждого уровня качества является желаемым фактором сжатия. Требуется уменьшение коэффициентов. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Получает или задает значение, указывающее, является ли [full frame]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Получает или задает значение, указывающее, использовать ли необратимое DWT 9‑7 (true) или без потерь DWT 5‑3 (по умолчанию). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Параметры многопостраничности |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Получает или задает обработчик события прогресса. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Получает или задает настройки разрешения. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Получает или задает параметры растеризации векторов. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |

## Примеры

В этом примере демонстрируется использование различных классов из пространства имен SaveOptions для экспорта. Изображение типа Psd загружается в экземпляр Image, а затем экспортируется в несколько форматов.

```csharp
[C#]

//Загрузите существующее изображение в экземпляр класса Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Экспорт в файловый формат BMP с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Экспорт в файловый формат JPEG с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Экспорт в файловый формат JPEG 2000 с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Экспорт в файловый формат PNG с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Экспорт в файловый формат TIFF с использованием параметров по умолчанию
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### См. также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


