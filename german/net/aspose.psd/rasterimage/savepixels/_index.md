---
title: "RasterImage.SavePixels"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RasterImage-Methode. Speichert die Pixel"
type: docs
weight: 540
url: /de/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

Speichert die Pixel.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Rechteck | Rectangle | Das Rechteck, in dem die Pixel gespeichert werden. |
| Pixel | Color[] | Das Pixel-Array. |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


