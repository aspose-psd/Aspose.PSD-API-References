---
title: Class Font
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Font klas. Definiert ein bestimmtes Format für Text einschließlich Schriftart Größe und Stilattributen. Diese Klasse kann nicht vererbt werden.
type: docs
weight: 4280
url: /de/net/aspose.psd/font/
---
## Font class

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stilattributen. Diese Klasse kann nicht vererbt werden.

```csharp
public sealed class Font
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initialisiert eine neue`Font` die die angegebene vorhandene verwendet`Font` Und[`FontStyle`](../fontstyle/) Aufzählung. |
| [Font](font/#constructor_1)(string, float) | Initialisiert eine neue`Font` unter Verwendung einer bestimmten Größe. Der Zeichensatz ist eingestellt aufDefault , die Grafikeinheit anPoint , den Schriftstil zuRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initialisiert eine neue`Font` unter Verwendung einer bestimmten Größe und eines bestimmten Stils. Der Zeichensatz ist eingestellt aufDefault , die Grafikeinheit anPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initialisiert eine neue`Font` unter Verwendung einer bestimmten Größe und Einheit. Der Zeichensatz ist eingestellt aufDefault der Stil ist eingestellt aufRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initialisiert eine neue`Font` unter Verwendung einer bestimmten Größe, eines Stils und einer Einheit. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initialisiert eine neue`Font` Verwenden einer bestimmten Größe, eines Stils, einer Einheit und eines Zeichensatzes. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Ruft einen Wert ab, der angibt, ob dies`Font` ist fett. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Ruft einen Bytewert ab, der den Zeichensatz angibt, den dieser verwendet`Font` verwendet. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Ruft einen Wert ab, der angibt, ob dies`Font`ist kursiv. |
| [Name](../../aspose.psd/font/name/) { get; } | Ruft den Gesichtsnamen davon ab`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Ruft die em-Größe davon ab`Font` gemessen in den von der angegebenen Einheiten[`Unit`](./unit/) Eigentum. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Ruft einen Wert ab, der angibt, ob dies`Font` gibt eine horizontale Linie durch die Schriftart an. |
| [Style](../../aspose.psd/font/style/) { get; } | Ruft Stilinformationen dafür ab`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Ruft einen Wert ab, der angibt, ob dies`Font` ist unterstrichen. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Liefert die Maßeinheit dafür`Font` . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Erstellt eine exakte tiefe Kopie davon`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Gibt an, ob das angegebene Objekt ein ist`Font` und hat die gleichen Eigenschaftswerte wie diese`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Ruft den Hash-Code dafür ab`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Gibt eine für Menschen lesbare Zeichenfolgendarstellung davon zurück`Font` . |

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

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


