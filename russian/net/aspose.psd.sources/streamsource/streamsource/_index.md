---
title: "StreamSource.StreamSource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор StreamSource. Инициализирует новый экземпляр класса StreamSource"
type: docs
weight: 10
url: /ru/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Инициализирует новый экземпляр класса [`StreamSource`](../).

```csharp
public StreamSource(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для открытия. |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Инициализирует новый экземпляр класса [`StreamSource`](../).

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток для открытия. |
| disposeStream | Boolean | если установить `true`, поток будет освобождён. |

## Примеры

Этот пример демонстрирует использование System.IO.Stream для создания нового файла Image.

```csharp
[C#]

//Создаёт экземпляр PsdOptions и задаёт его различные свойства.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создайте экземпляр System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Определите свойство source для экземпляра PsdOptions.
//Второй логический параметр определяет, будет ли Stream освобождён после выхода из области видимости.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Создаёт экземпляр Image и вызывает метод Create, передавая PsdOptions в качестве параметра, для инициализации объекта Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //выполнить некоторую обработку изображения
}
```

### См. также

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


