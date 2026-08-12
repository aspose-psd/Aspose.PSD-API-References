---
title: "Layer.Layer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор Layer. Инициализирует новый экземпляр класса Layer. Конструктор для отложенной инициализации"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

Инициализирует новый экземпляр класса [`Layer`](../). Конструктор для отложенной инициализации.

```csharp
public Layer()
```

## Примеры

В следующем примере показано, как можно рисовать на только что созданном слое, если используется простая версия конструктора в Aspose.PSD

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

    // нарисуйте прямоугольник с помощью инструмента Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // нарисуйте другой прямоугольник с помощью Solid Brush синего цвета
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Инициализирует новый экземпляр класса [`Layer`](../).

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| изображение | RasterImage | Изображение. |
| disposeImage | Boolean | если установлено `true` [dispose image]. |

## Примеры

Следующий код демонстрирует возможность загружать файлы изображений JPEG/PNG/и т.д. в PsdImage без прямой загрузки.

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### См. также

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Инициализирует новый экземпляр класса [`Layer`](../).

```csharp
public Layer(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток изображения |

## Примеры

В следующем примере показано, как можно добавить изображения Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif в виде слоев в PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Инициализирует новый экземпляр класса [`Layer`](../) из массивов байтов.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| границы | Rectangle | Границы слоя. |
| redBytes | Byte[] | Красные байты. |
| greenBytes | Byte[] | Зелёные байты. |
| blueBytes | Byte[] | Синие байты. |
| name | String | Имя слоя. |

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Массивы байтов не могут быть пустыми, и их длина должна соответствовать размерам границ (bounds.Width * bounds.Height) |

### См. также

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


