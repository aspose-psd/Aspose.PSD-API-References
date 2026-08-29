---
title: "Klasse FileCreateSource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Sources.FileCreateSource Klasse. Stellt eine Datei-Quelle zur Erstellung dar"
type: docs
weight: 6090
url: /de/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Stellt eine Dateiquelle für die Erstellung dar.

```csharp
public sealed class FileCreateSource : FileSource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initialisiert eine neue Instanz der `FileCreateSource`-Klasse. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initialisiert eine neue Instanz der `FileCreateSource`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Ermittelt den zu erstellenden Dateipfad. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Ermittelt einen Wert, der angibt, ob die Datei temporär sein wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Ermittelt den Stream-Container. |

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

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


