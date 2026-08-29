---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "StreamSource-Konstruktor. Initialisiert eine neue Instanz der StreamSource-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Initialisiert eine neue Instanz der [`StreamSource`](../)-Klasse.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der zu öffnende Stream. |

## Beispiele

Dieses Beispiel zeigt, wie Pixelinformationen in einem Array vom Typ Color geladen, das Array manipuliert und zurück zum Bild gesetzt werden. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im PSD-Format) mithilfe eines MemoryStream-Objekts.

```csharp
[C#]

//Erstelle eine Instanz von MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstelle eine Instanz von PsdOptions und setze deren verschiedene Eigenschaften, einschließlich der Source-Eigenschaft
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Erstelle eine Instanz von Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Hole die Pixel des Bildes, indem du den Bereich als Bildgrenze angibst
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Durchlaufe das Array und setze die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Setze die Farbe des indizierten Pixels auf Gelb
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Setze die Farbe des indizierten Pixels auf Blau
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Wende die Pixeländerungen auf das Bild an
        image.SavePixels(image.Bounds, pixels);

        // Speichere alle Änderungen.
        image.Save();
    }

    //Schreibe MemoryStream in eine Datei
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Siehe auch

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initialisiert eine neue Instanz der [`StreamSource`](../)-Klasse.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der zu öffnende Stream. |
| disposeStream | Boolean | Wenn auf `true` gesetzt, wird der Stream freigegeben. |

## Beispiele

Dieses Beispiel demonstriert die Verwendung von System.IO.Stream, um eine neue Bilddatei zu erstellen.

```csharp
[C#]

//Erstellt eine Instanz von PsdOptions und setzt deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstelle eine Instanz von System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definiere die Quell‑Eigenschaft für die Instanz von PsdOptions.
//Der zweite boolesche Parameter bestimmt, ob der Stream freigegeben wird, sobald er den Gültigkeitsbereich verlässt.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Erstellt eine Instanz von Image und ruft die Create‑Methode mit PsdOptions als Parameter auf, um das Image‑Objekt zu initialisieren.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch
}
```

### Siehe auch

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


