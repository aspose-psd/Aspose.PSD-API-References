---
title: DrawString
second_title: Справочник по Aspose.PSD для .NET API
description: Рисует указанную текстовую строку в указанном месте с указаннымBrushaspose.psd/brush а такжеFontaspose.psd/font объекты.
type: docs
weight: 320
url: /ru/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush) а также[`Font`](../../font) объекты.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Нить для рисования. |
| font | Font | [`Font`](../../font) который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush) который определяет цвет и текстуру нарисованного текста. |
| x | Single | Координата x левого верхнего угла нарисованного текста. |
| y | Single | Y-координата левого верхнего угла нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. -или- *s* нулевой. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush) а также[`Font`](../../font) объекты.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Нить для рисования. |
| font | Font | [`Font`](../../font) который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush) который определяет цвет и текстуру нарисованного текста. |
| point | PointF | [`PointF`](../../pointf) структура, определяющая левый верхний угол нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. -или- *s* нулевой. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush) а также[`Font`](../../font) объекты, использующие атрибуты форматирования указанных[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Нить для рисования. |
| font | Font | [`Font`](../../font) который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush) который определяет цвет и текстуру нарисованного текста. |
| x | Single | Координата x левого верхнего угла нарисованного текста. |
| y | Single | Y-координата левого верхнего угла нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat) который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, которые применяются к нарисованному тексту. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. -или- *s* нулевой. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush) а также[`Font`](../../font) объекты, использующие атрибуты форматирования указанных[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Нить для рисования. |
| font | Font | [`Font`](../../font) который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush) который определяет цвет и текстуру нарисованного текста. |
| point | PointF | [`PointF`](../../pointf) структура, определяющая левый верхний угол нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat) который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, которые применяются к нарисованному тексту. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. -или- *s* нулевой. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../../brush) а также[`Font`](../../font) объекты.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Нить для рисования. |
| font | Font | [`Font`](../../font) который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush) который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) структура, указывающая расположение нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. -или- *s* нулевой. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../../brush) а также[`Font`](../../font) объекты, использующие атрибуты форматирования указанных[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Нить для рисования. |
| font | Font | [`Font`](../../font) который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush) который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) структура, указывающая расположение нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat) который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, которые применяются к нарисованному тексту. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равно null. -или- *s* равно null. -или- *brush* нулевой. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* пространство имен [Aspose.PSD](../../graphics)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
