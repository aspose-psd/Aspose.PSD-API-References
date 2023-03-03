---
title: Image.Create
second_title: Aspose.PSD für .NET-API-Referenz
description: Image methode. Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.
type: docs
weight: 10
url: /de/net/aspose.psd/image/create/
---
## Image.Create method

Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Die Bildoptionen. |
| width | Int32 | Die Breite. |
| height | Int32 | Die Höhe. |

### Rückgabewert

Das neu erstellte Bild.

### Beispiele

In diesem Beispiel wird eine neue Bilddatei an einem Speicherort auf dem Datenträger erstellt, wie durch die Source-Eigenschaft der PsdOptions-Instanz angegeben. Mehrere Eigenschaften für die PsdOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von PsdOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von PsdOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create-Methode aufrufen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namensraum [Aspose.PSD](../../image/)
* Montage [Aspose.PSD](../../../)


