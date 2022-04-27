---
title: DrawString
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 320
url: /net/aspose.psd/graphics/drawstring/
---
## Graphics.DrawString method (1 of 6)

Draws the specified text string at the specified location with the specified [`Brush`](../../brush) and [`Font`](../../font) objects.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush) that determines the color and texture of the drawn text. |
| x | Single | The x-coordinate of the upper-left corner of the drawn text. |
| y | Single | The y-coordinate of the upper-left corner of the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namespace [Aspose.PSD](../../graphics)
* assembly [Aspose.PSD](../../../)

---

## Graphics.DrawString method (2 of 6)

Draws the specified text string at the specified location with the specified [`Brush`](../../brush) and [`Font`](../../font) objects.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush) that determines the color and texture of the drawn text. |
| point | PointF | [`PointF`](../../pointf) structure that specifies the upper-left corner of the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namespace [Aspose.PSD](../../graphics)
* assembly [Aspose.PSD](../../../)

---

## Graphics.DrawString method (3 of 6)

Draws the specified text string at the specified location with the specified [`Brush`](../../brush) and [`Font`](../../font) objects using the formatting attributes of the specified [`StringFormat`](../../stringformat).

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush) that determines the color and texture of the drawn text. |
| x | Single | The x-coordinate of the upper-left corner of the drawn text. |
| y | Single | The y-coordinate of the upper-left corner of the drawn text. |
| format | StringFormat | [`StringFormat`](../../stringformat) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namespace [Aspose.PSD](../../graphics)
* assembly [Aspose.PSD](../../../)

---

## Graphics.DrawString method (4 of 6)

Draws the specified text string at the specified location with the specified [`Brush`](../../brush) and [`Font`](../../font) objects using the formatting attributes of the specified [`StringFormat`](../../stringformat).

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush) that determines the color and texture of the drawn text. |
| point | PointF | [`PointF`](../../pointf) structure that specifies the upper-left corner of the drawn text. |
| format | StringFormat | [`StringFormat`](../../stringformat) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namespace [Aspose.PSD](../../graphics)
* assembly [Aspose.PSD](../../../)

---

## Graphics.DrawString method (5 of 6)

Draws the specified text string in the specified rectangle with the specified [`Brush`](../../brush) and [`Font`](../../font) objects.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush) that determines the color and texture of the drawn text. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) structure that specifies the location of the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. |

### See Also

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namespace [Aspose.PSD](../../graphics)
* assembly [Aspose.PSD](../../../)

---

## Graphics.DrawString method (6 of 6)

Draws the specified text string in the specified rectangle with the specified [`Brush`](../../brush) and [`Font`](../../font) objects using the formatting attributes of the specified [`StringFormat`](../../stringformat).

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| s | String | String to draw. |
| font | Font | [`Font`](../../font) that defines the text format of the string. |
| brush | Brush | [`Brush`](../../brush) that determines the color and texture of the drawn text. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) structure that specifies the location of the drawn text. |
| format | StringFormat | [`StringFormat`](../../stringformat) that specifies formatting attributes, such as line spacing and alignment, that are applied to the drawn text. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* is null. -or- *s* is null. -or- *brush* is null. |

### See Also

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namespace [Aspose.PSD](../../graphics)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
