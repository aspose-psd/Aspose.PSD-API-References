---
title: Image.Save
second_title: Справочник по Aspose.PSD для .NET API
description: Image метод. Сохраняет данные изображения в базовый поток.
type: docs
weight: 230
url: /ru/net/aspose.psd/image/save/
---
## Save() {#save}

Сохраняет данные изображения в базовый поток.

```csharp
public void Save()
```

### Смотрите также

* class [Image](../)
* пространство имен [Aspose.PSD](../../image/)
* сборка [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| options | ImageOptionsBase | Опции. |

### Примеры

В следующем примере показано, как вы можете экспортировать файлы Adobe Illustrator в формат PDF в Aspose.PSD.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

В следующем примере показано, что AsposePSD поддерживает экспорт файлов PSB в формат PSD.

```csharp
[C#]

// Поддержка сохранения PSB в формате PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Следующий код сохраняет PsdImage как документ PDF с выбираемым текстом.

```csharp
[C#]

// Сохранение PSD в PDF не обеспечивает выбор текста
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

В следующем примере показано, как вы можете экспортировать файл AI в формат PSD и PNG в Aspose.PSD.

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

В следующем примере показано, что выравнивание текста с помощью ITextPortion для языков с письмом справа налево работает правильно.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

В этом примере показаны простые шаги для сохранения изображения. Чтобы продемонстрировать эту операцию, мы загружаем существующий файл из некоторого места на диске, выполняем операцию поворота изображения и сохраняем изображение в формате файла Jpeg, используя путь к файлу.

```csharp
[C#]

//Создаем экземпляр класса изображения и инициализируем его существующим файлом через путь к файлу
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Поворачиваем изображение на 180 градусов вокруг оси X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // Сохраняем изображение как Jpeg в путь к файлу с настройками JpegOptions по умолчанию
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

В следующем примере показано, как можно изменить видимость LayerGroup в Aspose.PSD.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// вносим изменения в имена слоев и сохраняем их
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Отключаем все внутри группы
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

В следующем примере показано, как можно рисовать на вновь созданном слое, если в Aspose.PSD используется версия простого конструктора.

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // рисуем прямоугольник инструментом Перо
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // рисуем еще один прямоугольник сплошной кистью синего цвета
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

В следующем примере показано, что чтение и сохранение 16-битных PSD-файлов в оттенках серого в 16-битных на канал RGB работает правильно и без исключений.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Здесь не должно быть исключений.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

В следующем примере показано, что чтение и сохранение 16-битных файлов PSD в оттенках серого в 8-битных оттенках серого на канал работает правильно и без исключений.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Здесь не должно быть исключений.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

В следующем примере показано, как можно использовать режим наложения слоя PassThrough в Aspose.PSD.

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

В следующем примере показано, что процесс преобразования документов работает правильно и без исключений.

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

В следующем примере показано, что чтение и сохранение 16-битных PSD-файлов в оттенках серого работает правильно и без исключений.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // Здесь не должно быть исключений.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* пространство имен [Aspose.PSD](../../image/)
* сборка [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| options | ImageOptionsBase | Варианты. |
| boundsRectangle | Rectangle | Конечный образ ограничивает прямоугольник. Установите пустой прямоугольник для использования исходных границ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | параметры |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Не удалось сохранить изображение. |

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* пространство имен [Aspose.PSD](../../image/)
* сборка [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который сохраняются данные изображения. |
| optionsBase | ImageOptionsBase | Варианты сохранения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | вариантыБаза |
| ArgumentException | Невозможно сохранить в указанном формате, так как в данный момент он не поддерживается.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Не удалось экспортировать изображение. |

### Примеры

В этом примере показан процесс сохранения изображения в MemoryStream. Чтобы продемонстрировать эту операцию, пример загружает существующий файл из некоторого места на диске, выполняет операцию поворота изображения и сохраняет изображение в формате Gif.

```csharp
[C#]

//Создаем экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Создаем экземпляр класса изображения и инициализируем его существующим файлом через путь к файлу
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // Поворачиваем изображение на 180 градусов вокруг оси X
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        // Сохраняем изображение в формате PSD в MemoryStream с настройками GifOptions по умолчанию
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* пространство имен [Aspose.PSD](../../image/)
* сборка [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который сохраняются данные изображения. |
| optionsBase | ImageOptionsBase | Варианты сохранения. |
| boundsRectangle | Rectangle | Конечный образ ограничивает прямоугольник. Установите пустой прямоугольник для использования исходных границ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | вариантыБаза |
| ArgumentException | Невозможно сохранить в указанном формате, так как в данный момент он не поддерживается.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Не удалось экспортировать изображение. |

### Смотрите также

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* пространство имен [Aspose.PSD](../../image/)
* сборка [Aspose.PSD](../../../)


