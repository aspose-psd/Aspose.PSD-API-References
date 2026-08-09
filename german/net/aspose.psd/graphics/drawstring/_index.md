---
title: "Graphics.DrawString"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Graphics-Methode. Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen Brush- und Font-Objekten."
type: docs
weight: 330
url: /de/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [`Brush`](../../brush/) und [`Font`](../../font/) Objekten.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Zu zeichnende Zeichenkette. |
| font | Font | [`Font`](../../font/) der das Textformat der Zeichenkette definiert. |
| brush | Brush | [`Brush`](../../brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | Single | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [`Brush`](../../brush/) und [`Font`](../../font/) Objekten.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Zu zeichnende Zeichenkette. |
| font | Font | [`Font`](../../font/) der das Textformat der Zeichenkette definiert. |
| brush | Brush | [`Brush`](../../brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | PointF | [`PointF`](../../pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. |

## Beispiele

Dieses Beispiel demonstriert die Verwendung der Font- und SolidBrush-Klasse zum Zeichnen von Zeichenketten auf einer Image-Oberfläche. Das Beispiel erstellt ein neues Image und zeichnet Formen mithilfe von Figures und GraphicsPath

```csharp
[C#]

//Erstellt eine Instanz von Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erstellt und initialisiert eine Instanz der Graphics-Klasse
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Löscht die Graphics-Oberfläche
    graphics.Clear(Color.Wheat);

    //Erstellt eine Instanz von Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Erstellt eine Instanz von SolidBrush mit roter Farbe
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Zeichne einen String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // Exportoptionen erstellen.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // Alle Änderungen speichern
    image.Save("C:\\temp\\output.gif", options);
}
```

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [`Brush`](../../brush/) und [`Font`](../../font/) Objekten unter Verwendung der Formatattribute des angegebenen [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Zu zeichnende Zeichenkette. |
| font | Font | [`Font`](../../font/) der das Textformat der Zeichenkette definiert. |
| brush | Brush | [`Brush`](../../brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | Single | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| format | StringFormat | [`StringFormat`](../../stringformat/) der Formatattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Position mit den angegebenen [`Brush`](../../brush/) und [`Font`](../../font/) Objekten unter Verwendung der Formatattribute des angegebenen [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Zu zeichnende Zeichenkette. |
| font | Font | [`Font`](../../font/) der das Textformat der Zeichenkette definiert. |
| brush | Brush | [`Brush`](../../brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | PointF | [`PointF`](../../pointf/) Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |
| format | StringFormat | [`StringFormat`](../../stringformat/) der Formatattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [`Brush`](../../brush/) und [`Font`](../../font/) Objekten.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Zu zeichnende Zeichenkette. |
| font | Font | [`Font`](../../font/) der das Textformat der Zeichenkette definiert. |
| brush | Brush | [`Brush`](../../brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Zeichnet die angegebene Textzeichenfolge im angegebenen Rechteck mit den angegebenen [`Brush`](../../brush/) und [`Font`](../../font/) Objekten unter Verwendung der Formatattribute des angegebenen [`StringFormat`](../../stringformat/).

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Zu zeichnende Zeichenkette. |
| font | Font | [`Font`](../../font/) der das Textformat der Zeichenkette definiert. |
| brush | Brush | [`Brush`](../../brush/) der die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die den Ort des gezeichneten Textes angibt. |
| format | StringFormat | [`StringFormat`](../../stringformat/) der Formatattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. -oder- *brush* ist null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


