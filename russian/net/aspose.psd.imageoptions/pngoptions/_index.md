---
title: PngOptions
second_title: Справочник по Aspose.PSD для .NET API
description: Параметры создания файла формата png.
type: docs
weight: 4760
url: /ru/net/aspose.psd.imageoptions/pngoptions/
---
## PngOptions class

Параметры создания файла формата png.

```csharp
public class PngOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngOptions](pngoptions#constructor)() | Инициализирует новый экземпляр класса[`PngOptions`](../pngoptions). |
| [PngOptions](pngoptions#constructor_1)(PngOptions) | Инициализирует новый экземпляр класса[`PngOptions`](../pngoptions). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth) { get; set; } | Разрядность. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype) { get; set; } | Получает или задает тип цвета. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel) { get; set; } | Уровень сжатия изображения png в диапазоне от 0 до 9, где 9 — максимальное сжатие, а 0 — режим сохранения. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Получает или задает замещающий шрифт по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если существующий шрифт слоя в PSD-файле не представлен в системе). Чтобы взять правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] семейства = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype) { get; set; } | Получает или задает тип фильтра, используемый во время процесса сохранения png-файла. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive) { get; set; } | Получает или задает значение, указывающее, является ли этот[`PngOptions`](../pngoptions)прогрессивным. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel) | Уровень сжатия по умолчанию. |

### Примеры

В следующем примере показано, как вы можете экспортировать файл AI в формат PSD и PNG в Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Этот пример демонстрирует использование различных классов из пространства имен SaveOptions для целей экспорта. Изображение типа Psd загружается в экземпляр Image, а затем экспортируется в несколько форматов.

```csharp
[C#]

//Загружаем существующее изображение в экземпляр класса Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Экспорт в формат файла BMP, используя параметры по умолчанию
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    // Экспорт в формат файла JPEG с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    // Экспорт в формат файла JPEG 2000 с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    // Экспорт в формат файла PNG с параметрами по умолчанию
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    // Экспорт в формат файла TIFF с параметрами по умолчанию
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

В следующем примере показано, как можно использовать режим наложения слоя PassThrough в Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Следующий пример демонстрирует, что процесс преобразования документов работает корректно и без исключений.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

В этом примере класс Graphics используется для создания примитивных форм на поверхности изображения. Чтобы продемонстрировать операцию, в примере создается новое изображение в формате PSD и рисуются примитивные фигуры на поверхности изображения с помощью методов Draw, предоставляемых классом Graphics, а затем экспортируется в формат файла PSD.

```csharp
[C#]

//Создаем экземпляр изображения 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем и инициализируем экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить графическую поверхность
    graphics.Clear(Color.Wheat);

    // Нарисуйте дугу, указав объект Pen, имеющий черный цвет, 
    //прямоугольник, окружающий дугу, начальный угол и угол развертки
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // Нарисуйте кривую Безье, задав объект Pen синего цвета и координаты Points.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Нарисуйте кривую, указав объект Pen зеленого цвета и массив точек
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    // Нарисовать линию 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // Нарисовать сегмент пирога
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // Нарисуйте многоугольник, указав объект Pen красного цвета и массив точек
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // Рисуем прямоугольник
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Создаем объект SolidBrush и устанавливаем его различные свойства
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Нарисуйте строку, используя объект SolidBrush и шрифт, в определенной точке
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Создаем экземпляр PngOptions и устанавливаем его различные свойства
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // сохранить все изменения.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* пространство имен [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
