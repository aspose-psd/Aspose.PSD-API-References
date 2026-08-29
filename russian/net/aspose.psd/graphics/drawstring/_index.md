---
title: "Graphics.DrawString"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Graphics. Рисует указанный текст в заданном месте с указанными объектами Brush и Font"
type: docs
weight: 330
url: /ru/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Рисует указанный текст в заданном месте с указанными объектами [`Brush`](../../brush/) и [`Font`](../../font/).

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font/) который определяет формат текста строки. |
| brush | Brush | [`Brush`](../../brush/) который определяет цвет и текстуру нарисованного текста. |
| x | Single | Координата x левого верхнего угла нарисованного текста. |
| y | Single | Координата y левого верхнего угла нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *s* равен null. |

### См. также

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Рисует указанный текст в заданном месте с указанными объектами [`Brush`](../../brush/) и [`Font`](../../font/).

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font/) который определяет формат текста строки. |
| brush | Brush | [`Brush`](../../brush/) который определяет цвет и текстуру нарисованного текста. |
| point | PointF | [`PointF`](../../pointf/) структура, определяющая левый верхний угол нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *s* равен null. |

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

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Рисует указанный текст в заданном месте с указанными объектами [`Brush`](../../brush/) и [`Font`](../../font/), используя атрибуты форматирования указанного [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font/) который определяет формат текста строки. |
| brush | Brush | [`Brush`](../../brush/) который определяет цвет и текстуру нарисованного текста. |
| x | Single | Координата x левого верхнего угла нарисованного текста. |
| y | Single | Координата y левого верхнего угла нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat/) который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *s* равен null. |

### См. также

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Рисует указанный текст в заданном месте с указанными объектами [`Brush`](../../brush/) и [`Font`](../../font/), используя атрибуты форматирования указанного [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font/) который определяет формат текста строки. |
| brush | Brush | [`Brush`](../../brush/) который определяет цвет и текстуру нарисованного текста. |
| point | PointF | [`PointF`](../../pointf/) структура, определяющая левый верхний угол нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat/) который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *s* равен null. |

### См. также

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Рисует указанный текст в заданном прямоугольнике с указанными объектами [`Brush`](../../brush/) и [`Font`](../../font/).

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font/) который определяет формат текста строки. |
| brush | Brush | [`Brush`](../../brush/) который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) структура, определяющая расположение нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *s* равен null. |

### См. также

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Рисует указанный текст в заданном прямоугольнике с указанными объектами [`Brush`](../../brush/) и [`Font`](../../font/), используя атрибуты форматирования указанного [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font/) который определяет формат текста строки. |
| brush | Brush | [`Brush`](../../brush/) который определяет цвет и текстуру нарисованного текста. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) структура, определяющая расположение нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat/) который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, применяемые к нарисованному тексту. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* равен null. -or- *s* равен null. -or- *brush* равен null. |

### См. также

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


