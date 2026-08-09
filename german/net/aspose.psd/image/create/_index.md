---
title: "Image.Create"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Image-Methode. Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen"
type: docs
weight: 10
url: /de/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Die Bildoptionen. |
| Breite | Int32 | Die Breite. |
| Höhe | Int32 | Die Höhe. |

### Rückgabewert

Das neu erstellte Bild.

## Beispiele

Dieses Beispiel erstellt eine neue Bilddatei an einem Speicherort, der durch die Source‑Eigenschaft der PsdOptions‑Instanz angegeben ist. Mehrere Eigenschaften der PsdOptions‑Instanz werden gesetzt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source‑Eigenschaft, die in diesem Fall auf den tatsächlichen Speicherort verweist.

```csharp
[C#]

//Erstellen Sie eine Instanz von PsdOptions und setzen Sie deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von PsdOptions zu.
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create‑Methode aufrufen.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


