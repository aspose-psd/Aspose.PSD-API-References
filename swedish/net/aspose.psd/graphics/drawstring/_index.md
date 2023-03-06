---
title: Graphics.DrawString
second_title: Aspose.PSD för .NET API-referens
description: Graphics metod. Ritar den angivna textsträngen på den angivna platsen med den angivnaBrush ochFont objekt.
type: docs
weight: 320
url: /sv/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush/) och[`Font`](../../font/) objekt.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font/) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush/) som bestämmer färgen och strukturen på den ritade texten. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush/) och[`Font`](../../font/) objekt.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font/) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush/) som bestämmer färgen och strukturen på den ritade texten. |
| point | PointF | [`PointF`](../../pointf/) struktur som anger det övre vänstra hörnet av den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Exempel

Det här exemplet visar användningen av klassen Font och SolidBrush för att rita strängar på bildytan. Exemplet skapar en ny bild och ritar former med hjälp av Figurer och GraphicsPath

```csharp
[C#]

//Skapar en instans av bild
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Skapar och initierar en instans av klassen Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Rensar grafikytan
    graphics.Clear(Color.Wheat);

    //Skapar en instans av Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Rita ett snöre
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // skapa exportalternativ.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // spara alla ändringar
    image.Save("C:\\temp\\output.gif", options);
}
```

### Se även

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush/) och[`Font`](../../font/) objekt som använder formateringsattributen för de angivna[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font/) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush/) som bestämmer färgen och strukturen på den ritade texten. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |
| format | StringFormat | [`StringFormat`](../../stringformat/) som anger formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush/) och[`Font`](../../font/) objekt som använder formateringsattributen för de angivna[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font/) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush/) som bestämmer färgen och strukturen på den ritade texten. |
| point | PointF | [`PointF`](../../pointf/) struktur som anger det övre vänstra hörnet av den ritade texten. |
| format | StringFormat | [`StringFormat`](../../stringformat/) som anger formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../../brush/) och[`Font`](../../font/) objekt.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font/) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush/) som bestämmer färgen och strukturen på den ritade texten. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) struktur som anger platsen för den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../../brush/) och[`Font`](../../font/) objekt som använder formateringsattributen för de angivna[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font/) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush/) som bestämmer färgen och strukturen på den ritade texten. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) struktur som anger platsen för den ritade texten. |
| format | StringFormat | [`StringFormat`](../../stringformat/) som anger formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är null. -eller- *brush* är inget. |

### Se även

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namnutrymme [Aspose.PSD](../../graphics/)
* hopsättning [Aspose.PSD](../../../)


