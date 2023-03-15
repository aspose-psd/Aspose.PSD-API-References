---
title: Layer.Layer
second_title: Справочник по Aspose.PSD для .NET API
description: Layer строитель. Инициализирует новый экземплярLayer сорт. Конструктор для ленивой инициализации.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Инициализирует новый экземпляр[`Layer`](../) сорт. Конструктор для ленивой инициализации.

```csharp
public Layer()
```

### Примеры

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

### Смотрите также

* class [Layer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* сборка [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Инициализирует новый экземпляр[`Layer`](../) класс.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | RasterImage | Изображение. |
| disposeImage | Boolean | если установлено`истинный` [удалить изображение]. |

### Примеры

Следующий код демонстрирует возможность загрузки файлов изображений JPEG/PNG/и т. д. в PsdImage без прямой загрузки.

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

### Смотрите также

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* сборка [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Инициализирует новый экземпляр[`Layer`](../) класс.

```csharp
public Layer(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток изображений |

### Примеры

В следующем примере показано, как можно добавлять изображения Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif в качестве слоев в PsdImage.

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

### Смотрите также

* class [Layer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* сборка [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Инициализирует новый экземпляр[`Layer`](../) класс из байтовых массивов.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bounds | Rectangle | Границы слоя. |
| redBytes | Byte[] | Красные байты. |
| greenBytes | Byte[] | Зеленые байты. |
| blueBytes | Byte[] | Синие байты. |
| name | String | Имя слоя. |

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Массивы байтов не могут быть пустыми или Длина массивов байтов должна равняться размерам границ (bounds.Width * bounds.Height) |

### Смотрите также

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* сборка [Aspose.PSD](../../../)


