---
title: Graphics.DrawString
second_title: Aspose.PSD voor .NET API-referentie
description: Graphics methode. Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegevenBrush EnFont objecten.
type: docs
weight: 320
url: /nl/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../../brush/) En[`Font`](../../font/) objecten.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | String | String om te tekenen. |
| font | Font | [`Font`](../../font/) die de tekstopmaak van de tekenreeks definieert. |
| brush | Brush | [`Brush`](../../brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| x | Single | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | Single | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *brush* is nul. -of- *s* is niets. |

### Zie ook

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../../brush/) En[`Font`](../../font/) objecten.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | String | String om te tekenen. |
| font | Font | [`Font`](../../font/) die de tekstopmaak van de tekenreeks definieert. |
| brush | Brush | [`Brush`](../../brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| point | PointF | [`PointF`](../../pointf/) structuur die de linkerbovenhoek van de getekende tekst specificeert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *brush* is nul. -of- *s* is niets. |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van de klasse Font en SolidBrush om tekenreeksen op het afbeeldingsoppervlak te tekenen. In het voorbeeld wordt een nieuwe afbeelding gemaakt en vormen getekend met behulp van Figuren en GraphicsPath

```csharp
[C#]

//Maakt een exemplaar van Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Creëert en initialiseert een instantie van de klasse Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Wist grafisch oppervlak
    graphics.Clear(Color.Wheat);

    //Maakt een exemplaar van Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // Maak een exemplaar van SolidBrush met rode kleur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Teken een string
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // creëer exportopties.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // sla alle veranderingen op
    image.Save("C:\\temp\\output.gif", options);
}
```

### Zie ook

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../../brush/) En[`Font`](../../font/) objecten met behulp van de opmaakkenmerken van het opgegeven[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | String | String om te tekenen. |
| font | Font | [`Font`](../../font/) die de tekstopmaak van de tekenreeks definieert. |
| brush | Brush | [`Brush`](../../brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| x | Single | De x-coördinaat van de linkerbovenhoek van de getekende tekst. |
| y | Single | De y-coördinaat van de linkerbovenhoek van de getekende tekst. |
| format | StringFormat | [`StringFormat`](../../stringformat/) dat opmaakkenmerken specificeert, zoals regelafstand en uitlijning, die worden toegepast op de getekende tekst. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *brush* is nul. -of- *s* is niets. |

### Zie ook

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Tekent de opgegeven tekenreeks op de opgegeven locatie met de opgegeven[`Brush`](../../brush/) En[`Font`](../../font/) objecten met behulp van de opmaakkenmerken van het opgegeven[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | String | String om te tekenen. |
| font | Font | [`Font`](../../font/) die de tekstopmaak van de tekenreeks definieert. |
| brush | Brush | [`Brush`](../../brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| point | PointF | [`PointF`](../../pointf/) structuur die de linkerbovenhoek van de getekende tekst specificeert. |
| format | StringFormat | [`StringFormat`](../../stringformat/) dat opmaakkenmerken specificeert, zoals regelafstand en uitlijning, die worden toegepast op de getekende tekst. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *brush* is nul. -of- *s* is niets. |

### Zie ook

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven[`Brush`](../../brush/) En[`Font`](../../font/) objecten.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | String | String om te tekenen. |
| font | Font | [`Font`](../../font/) die de tekstopmaak van de tekenreeks definieert. |
| brush | Brush | [`Brush`](../../brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) structuur die de locatie van de getekende tekst specificeert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *brush* is nul. -of- *s* is niets. |

### Zie ook

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Tekent de opgegeven tekenreeks in de opgegeven rechthoek met de opgegeven[`Brush`](../../brush/) En[`Font`](../../font/) objecten met behulp van de opmaakkenmerken van het opgegeven[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | String | String om te tekenen. |
| font | Font | [`Font`](../../font/) die de tekstopmaak van de tekenreeks definieert. |
| brush | Brush | [`Brush`](../../brush/) die de kleur en textuur van de getekende tekst bepaalt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) structuur die de locatie van de getekende tekst specificeert. |
| format | StringFormat | [`StringFormat`](../../stringformat/) dat opmaakkenmerken specificeert, zoals regelafstand en uitlijning, die worden toegepast op de getekende tekst. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *brush* is nul. -of- *s* is nul. -of- *brush* is niets. |

### Zie ook

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* naamruimte [Aspose.PSD](../../graphics/)
* montage [Aspose.PSD](../../../)


