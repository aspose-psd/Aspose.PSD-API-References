---
title: Class Font
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Font сорт. Определяет определенный формат текста включая начертание шрифта размер и атрибуты стиля. Этот класс не может быть унаследован.
type: docs
weight: 4280
url: /ru/net/aspose.psd/font/
---
## Font class

Определяет определенный формат текста, включая начертание шрифта, размер и атрибуты стиля. Этот класс не может быть унаследован.

```csharp
public sealed class Font
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Инициализирует новый`Font` который использует указанный существующий`Font` и[`FontStyle`](../fontstyle/) перечисление. |
| [Font](font/#constructor_1)(string, float) | Инициализирует новый`Font` используя заданный размер. Набор символов установлен наDefault , графический блок кPoint , стиль шрифта дляRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Инициализирует новый`Font` с использованием определенного размера и стиля. Набор символов установлен наDefault , графический блок кPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Инициализирует новый`Font` используя указанный размер и единицу измерения. Набор символов установлен наDefault стиль установлен наRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Инициализирует новый`Font` используя указанный размер, стиль и единицу измерения. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Инициализирует новый`Font` используя указанный размер, стиль, единицу измерения и набор символов. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Получает значение, указывающее, является ли это`Font` выделен жирным шрифтом. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Получает значение байта, указывающее набор символов, который`Font` использует. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Получает значение, указывающее, является ли это`Font`выделено курсивом. |
| [Name](../../aspose.psd/font/name/) { get; } | Получает имя лица этого`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Получает размер em этого`Font` измеряется в единицах, указанных[`Unit`](./unit/) свойство. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Получает значение, указывающее, является ли это`Font` определяет горизонтальную линию через шрифт. |
| [Style](../../aspose.psd/font/style/) { get; } | Получает информацию о стиле для этого`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Получает значение, указывающее, является ли это`Font` подчеркнуто. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Получает единицу измерения для этого`Font` . |

## Методы

| Имя | Описание |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Создает точную глубокую копию этого`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Указывает, является ли указанный объект`Font` и имеет те же значения свойств, что и этот`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Получает хэш-код для этого`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Возвращает удобочитаемое строковое представление этого`Font` . |

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

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


