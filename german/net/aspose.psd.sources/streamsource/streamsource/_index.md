---
title: StreamSource.StreamSource
second_title: Aspose.PSD für .NET-API-Referenz
description: StreamSource constructeur. Initialisiert eine neue Instanz vonStreamSource Klasse.
type: docs
weight: 10
url: /de/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Initialisiert eine neue Instanz von[`StreamSource`](../) Klasse.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der zu öffnende Stream. |

### Beispiele

Dieses Beispiel zeigt, wie Pixelinformationen in ein Array vom Typ Color geladen, das Array manipuliert und wieder auf das Bild gesetzt wird. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im PSD-Format) mit dem MemoryStream-Objekt.

```csharp
[C#]

//Eine Instanz von MemoryStream erstellen
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstellen Sie eine Instanz von PsdOptions und legen Sie die verschiedenen Eigenschaften einschließlich der Source-Eigenschaft fest
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Die Pixel des Bildes abrufen, indem der Bereich als Bildgrenze angegeben wird
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // Schleife über das Array und setzt die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Indizierte Pixelfarbe auf gelb setzen
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Indizierte Pixelfarbe auf Blau setzen
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Pixeländerungen auf das Bild anwenden
        image.SavePixels(image.Bounds, pixels);

        // Alle Änderungen speichern.
        image.Save();
    }

    //MemoryStream in Datei schreiben
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Siehe auch

* class [StreamSource](../)
* namensraum [Aspose.PSD.Sources](../../streamsource/)
* Montage [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initialisiert eine neue Instanz von[`StreamSource`](../) Klasse.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der zu öffnende Stream. |
| disposeStream | Boolean | wenn eingestellt`WAHR` Der Stream wird entsorgt. |

### Beispiele

Dieses Beispiel zeigt die Verwendung von System.IO.Stream zum Erstellen einer neuen Image-Datei

```csharp
[C#]

//Erzeugt eine Instanz von PsdOptions und legt ihre verschiedenen Eigenschaften fest
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von System.IO.Stream erstellen
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definieren Sie die Quelleigenschaft für die Instanz von PsdOptions
//Der zweite boolesche Parameter bestimmt, ob der Stream verworfen wird, sobald er den Gültigkeitsbereich verlässt
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Erzeugt eine Instanz von Image und ruft die Create-Methode mit PsdOptions als Parameter auf, um das Image-Objekt zu initialisieren   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen
}
```

### Siehe auch

* class [StreamSource](../)
* namensraum [Aspose.PSD.Sources](../../streamsource/)
* Montage [Aspose.PSD](../../../)


