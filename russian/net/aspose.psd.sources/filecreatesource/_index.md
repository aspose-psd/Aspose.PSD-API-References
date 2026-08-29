---
title: "Класс FileCreateSource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Sources.FileCreateSource. Представляет файловый источник для создания"
type: docs
weight: 6090
url: /ru/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Представляет файловый источник для создания.

```csharp
public sealed class FileCreateSource : FileSource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Инициализирует новый экземпляр класса `FileCreateSource`. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Инициализирует новый экземпляр класса `FileCreateSource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Получает путь к файлу для создания. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Получает значение, указывающее, будет ли файл временным. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Получает контейнер потока. |

## Примеры

Этот пример демонстрирует использование классов Font и SolidBrush для рисования строк на поверхности Image. Пример создает новый Image и рисует фигуры с помощью Figures и GraphicsPath

```csharp
[C#]

//Создает экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создает и инициализирует экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очищает поверхность Graphics
    graphics.Clear(Color.Wheat);

    //Создает экземпляр Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Создает экземпляр SolidBrush с красным цветом
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Рисует строку
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // создает параметры экспорта.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // сохранить все изменения
    image.Save("C:\\temp\\output.gif", options);
}
```

### См. также

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


