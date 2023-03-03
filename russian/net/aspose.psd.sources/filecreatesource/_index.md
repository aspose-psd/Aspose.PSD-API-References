---
title: Class FileCreateSource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Sources.FileCreateSource сорт. Представляет источник файла для создания.
type: docs
weight: 5590
url: /ru/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Представляет источник файла для создания.

```csharp
public sealed class FileCreateSource : FileSource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Инициализирует новый экземпляр`FileCreateSource` класс. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Инициализирует новый экземпляр`FileCreateSource` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Получает путь к файлу для создания. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Получает значение, указывающее, будет ли файл временным. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Получает контейнер потока. |

### Примеры

В этом примере демонстрируется использование класса Font и SolidBrush для рисования строк на поверхности изображения. В примере создается новое изображение и рисуются фигуры с использованием Figures и GraphicsPath.

```csharp
[C#]

// Создает экземпляр изображения
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создает и инициализирует экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очищает графическую поверхность
    graphics.Clear(Color.Wheat);

    // Создает экземпляр шрифта
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Создаем экземпляр SolidBrush красного цвета
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Рисуем строку
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // создаем параметры экспорта.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // сохранить все изменения
    image.Save("C:\\temp\\output.gif", options);
}
```

### Смотрите также

* class [FileSource](../filesource/)
* пространство имен [Aspose.PSD.Sources](../../aspose.psd.sources/)
* сборка [Aspose.PSD](../../)


