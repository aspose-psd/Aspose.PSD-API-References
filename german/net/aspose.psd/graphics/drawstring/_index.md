---
title: Graphics.DrawString
second_title: Aspose.PSD für .NET-API-Referenz
description: Graphics methode. Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenenBrush UndFont Objekte.
type: docs
weight: 320
url: /de/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush/) Und[`Font`](../../font/) Objekte.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font/) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush/) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | Single | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush/) Und[`Font`](../../font/) Objekte.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font/) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush/) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | PointF | [`PointF`](../../pointf/) -Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Beispiele

Dieses Beispiel demonstriert die Verwendung der Klassen Font und SolidBrush zum Zeichnen von Zeichenfolgen auf der Bildoberfläche. Das Beispiel erstellt ein neues Image und zeichnet Formen mit Figures und GraphicsPath

```csharp
[C#]

//Erzeugt eine Instanz von Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Erzeugt und initialisiert eine Instanz der Graphics-Klasse
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Löscht die Grafikoberfläche
    graphics.Clear(Color.Wheat);

    //Erzeugt eine Instanz von Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Eine Instanz von SolidBrush mit roter Farbe erstellen
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Zeichne einen String
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
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush/) Und[`Font`](../../font/) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font/) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush/) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | Single | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| format | StringFormat | [`StringFormat`](../../stringformat/) die Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush/) Und[`Font`](../../font/) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font/) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush/) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | PointF | [`PointF`](../../pointf/) -Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |
| format | StringFormat | [`StringFormat`](../../stringformat/) die Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Zeichnet die angegebene Textzeichenfolge in das angegebene Rechteck mit dem angegebenen[`Brush`](../../brush/) Und[`Font`](../../font/) Objekte.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font/) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush/) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die die Position des gezeichneten Textes angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Zeichnet die angegebene Textzeichenfolge in das angegebene Rechteck mit dem angegebenen[`Brush`](../../brush/) Und[`Font`](../../font/) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font/) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush/) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) Struktur, die die Position des gezeichneten Textes angibt. |
| format | StringFormat | [`StringFormat`](../../stringformat/) die Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. -oder- *brush* ist Null. |

### Siehe auch

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namensraum [Aspose.PSD](../../graphics/)
* Montage [Aspose.PSD](../../../)


