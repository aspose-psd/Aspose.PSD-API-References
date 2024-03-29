---
title: Class FileCreateSource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Sources.FileCreateSource klas. Stellt eine Dateiquelle für die Erstellung dar.
type: docs
weight: 5590
url: /de/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Stellt eine Dateiquelle für die Erstellung dar.

```csharp
public sealed class FileCreateSource : FileSource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initialisiert eine neue Instanz von`FileCreateSource` Klasse. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initialisiert eine neue Instanz von`FileCreateSource` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Ruft den zu erstellenden Dateipfad ab. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Ruft einen Wert ab, der angibt, ob die Datei temporal sein wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Ruft den Stream-Container ab. |

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

* class [FileSource](../filesource/)
* namensraum [Aspose.PSD.Sources](../../aspose.psd.sources/)
* Montage [Aspose.PSD](../../)


