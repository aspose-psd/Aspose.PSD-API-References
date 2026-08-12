---
title: "Класс Font"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Font. Определяет конкретный формат текста, включая размер шрифта и атрибуты стиля. Этот класс не может быть наследован."
type: docs
weight: 4750
url: /ru/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Определяет определённый формат текста, включая гарнитуру шрифта, размер и атрибуты стиля. Этот класс не может быть унаследован.

```csharp
public sealed class Font
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Инициализирует новый `Font`, который использует указанный существующий `Font` и перечисление [`FontStyle`](../fontstyle/). |
| [Font](font/#constructor_1)(string, float) | Инициализирует новый `Font`, используя указанный размер. Набор символов установлен в Default, графическая единица — Point, стиль шрифта — Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Инициализирует новый `Font`, используя указанный размер и стиль. Набор символов установлен в Default, графическая единица — Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Инициализирует новый `Font`, используя указанный размер и единицу измерения. Набор символов установлен в Default, стиль установлен в Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Инициализирует новый `Font`, используя указанный размер, стиль и единицу измерения. Набор символов установлен в Default, стиль установлен в Regular. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Инициализирует новый `Font`, используя указанный размер, стиль, единицу измерения и набор символов. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Получает значение, указывающее, является ли этот `Font` полужирным. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Получает байтовое значение, которое указывает набор символов, используемый этим `Font`. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Получает значение, указывающее, является ли этот `Font` курсивным. |
| [Name](../../aspose.psd/font/name/) { get; } | Получает название гарнитуры этого `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | Получает размер em этого `Font`, измеренный в единицах, указанных свойством [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Получает значение, указывающее, задаёт ли этот `Font` горизонтальную линию через шрифт. |
| [Style](../../aspose.psd/font/style/) { get; } | Получает информацию о стиле этого `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Получает значение, указывающее, подчёркнут ли этот `Font`. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Получает единицу измерения для этого `Font`. |

## Методы

| Имя | Описание |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Создаёт точную глубокую копию этого `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Указывает, является ли указанный объект `Font` и имеет ли такие же значения свойств, как у этого `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Получает хеш-код для этого `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | Возвращает человекочитаемое строковое представление этого `Font`. |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


