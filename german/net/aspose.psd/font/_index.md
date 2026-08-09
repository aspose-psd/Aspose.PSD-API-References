---
title: "Klasse Font"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Font‑Klasse. Definiert ein bestimmtes Format für Text, einschließlich Schriftgröße und Stil‑Attribute. Diese Klasse kann nicht abgeleitet werden."
type: docs
weight: 4750
url: /de/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute. Diese Klasse kann nicht abgeleitet werden.

```csharp
public sealed class Font
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initialisiert ein neues `Font`, das das angegebene vorhandene `Font` und die [`FontStyle`](../fontstyle/)‑Aufzählung verwendet. |
| [Font](font/#constructor_1)(string, float) | Initialisiert ein neues `Font` mit einer angegebenen Größe. Der Zeichensatz wird auf Default gesetzt, die Grafikeinheit auf Point, der Schriftstil auf Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initialisiert ein neues `Font` mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf Default gesetzt, die Grafikeinheit auf Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initialisiert ein neues `Font` mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf Default gesetzt, der Stil wird auf Regular gesetzt. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initialisiert ein neues `Font` mit einer angegebenen Größe, einem Stil und einer Einheit. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initialisiert ein neues `Font` mit einer angegebenen Größe, einem Stil, einer Einheit und einem Zeichensatz. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Gibt einen Wert zurück, der angibt, ob diese `Font` fett ist. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Gibt einen Byte-Wert zurück, der den Zeichensatz angibt, den diese `Font` verwendet. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Gibt einen Wert zurück, der angibt, ob diese `Font` kursiv ist. |
| [Name](../../aspose.psd/font/name/) { get; } | Gibt den Schriftartnamen dieser `Font` zurück. |
| [Size](../../aspose.psd/font/size/) { get; } | Gibt die Em-Größe dieser `Font` zurück, gemessen in den Einheiten, die durch die [`Unit`](./unit/)‑Eigenschaft angegeben sind. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Gibt einen Wert zurück, der angibt, ob diese `Font` eine horizontale Linie durch die Schrift definiert. |
| [Style](../../aspose.psd/font/style/) { get; } | Gibt Stilinformationen für diese `Font` zurück. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Gibt einen Wert zurück, der angibt, ob diese `Font` unterstrichen ist. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Gibt die Maßeinheit für diese `Font` zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Erstellt eine exakte tiefe Kopie dieser `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Gibt an, ob das angegebene Objekt ein `Font` ist und dieselben Eigenschaftswerte wie dieses `Font` hat. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Gibt den Hashcode für diese `Font` zurück. |
| override [ToString](../../aspose.psd/font/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser `Font` zurück. |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


