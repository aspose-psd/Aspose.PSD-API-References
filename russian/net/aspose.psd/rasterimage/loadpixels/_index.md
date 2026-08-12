---
title: "RasterImage.LoadPixels"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RasterImage. Загружает пиксели."
type: docs
weight: 410
url: /ru/net/aspose.psd/rasterimage/loadpixels/
---
{{< psd/tize >}}
## RasterImage.LoadPixels method

Загружает пиксели.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| прямоугольник | Rectangle | Прямоугольник, из которого загружаются пиксели. |

### Возвращаемое значение

Загруженный массив пикселей.

## Примеры

В этом примере показано, как загрузить информацию о пикселях в массив типа Color, изменить массив и установить его обратно в изображение. Для выполнения этих операций пример создаёт новый файл Image (в формате PSD) с использованием объекта MemoryStream.

```csharp
[C#]

//Создайте экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Создайте экземпляр PsdOptions и задайте его различные свойства, включая свойство Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Создайте экземпляр Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Получите пиксели изображения, указав область как границу изображения
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Пройдите по Array и установите цвет альтернативного индексированного пикселя
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Установите цвет индексированного пикселя в желтый
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Установите цвет индексированного пикселя в синий
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Примените изменения пикселей к изображению
        image.SavePixels(image.Bounds, pixels);

        // Сохраните все изменения.
        image.Save();
    }

    //Запишите MemoryStream в файл
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### См. также

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


