---
title: DrawString
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Disegna la stringa di testo specificata nella posizione specificata con loggetto specificatoBrushaspose.psd/brush eFontaspose.psd/font oggetti.
type: docs
weight: 320
url: /it/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| x | Single | La coordinata x dell'angolo superiore sinistro del testo disegnato. |
| y | Single | La coordinata y dell'angolo superiore sinistro del testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| point | PointF | [`PointF`](../../pointf) struttura che specifica l'angolo superiore sinistro del testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Esempi

Questo esempio illustra l'uso della classe Font e SolidBrush per disegnare stringhe su Image Surface. L'esempio crea una nuova immagine e disegna forme usando Figures e GraphicsPath

```csharp
[C#]

//Crea un'istanza di Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Cancella la superficie grafica
    graphics.Clear(Color.Wheat);

    //Crea un'istanza di Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crea un'istanza di SolidBrush con colore rosso
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Disegna una stringa
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crea opzioni di esportazione.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // salva tutte le modifiche
    image.Save("C:\\temp\\output.gif", options);
}
```

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| x | Single | La coordinata x dell'angolo superiore sinistro del testo disegnato. |
| y | Single | La coordinata y dell'angolo superiore sinistro del testo disegnato. |
| format | StringFormat | [`StringFormat`](../../stringformat) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Disegna la stringa di testo specificata nella posizione specificata con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| point | PointF | [`PointF`](../../pointf) struttura che specifica l'angolo superiore sinistro del testo disegnato. |
| format | StringFormat | [`StringFormat`](../../stringformat) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Disegna la stringa di testo specificata nel rettangolo specificato con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) struttura che specifica la posizione del testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Disegna la stringa di testo specificata nel rettangolo specificato con l'oggetto specificato[`Brush`](../../brush) e[`Font`](../../font) oggetti che utilizzano gli attributi di formattazione dell'oggetto specificato[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | String | Stringa da disegnare. |
| font | Font | [`Font`](../../font) che definisce il formato del testo della stringa. |
| brush | Brush | [`Brush`](../../brush) che determina il colore e la consistenza del testo disegnato. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) struttura che specifica la posizione del testo disegnato. |
| format | StringFormat | [`StringFormat`](../../stringformat) che specifica gli attributi di formattazione, come l'interlinea e l'allineamento, che vengono applicati al testo disegnato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *brush* è nullo. -o- *s* è nullo. -o- *brush* è zero. |

### Guarda anche

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* spazio dei nomi [Aspose.PSD](../../graphics)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
