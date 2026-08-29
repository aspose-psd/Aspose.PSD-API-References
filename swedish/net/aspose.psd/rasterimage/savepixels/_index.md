---
title: "RasterImage.SavePixels"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RasterImage-metod. Sparar pixlarna"
type: docs
weight: 540
url: /sv/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

Sparar pixlarna.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rektangel | Rectangle | Rektangeln att spara pixlar till. |
| pixlar | Color[] | Pixelarrayen. |

## Exempel

Detta exempel visar hur man laddar pixelinformation i en array av typen Color, manipulerar arrayen och sätter tillbaka den i bilden. För att utföra dessa operationer skapar detta exempel en ny bildfil (i PSD-format) med hjälp av ett MemoryStream‑objekt.

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av PsdOptions och ange dess olika egenskaper inklusive Source‑egenskapen
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Skapa en instans av Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Hämta bildens pixlar genom att specificera området som bildens gräns
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loopa över arrayen och sätter färg på alternativt indexerad pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Sätt färgen på den indexerade pixeln till gul
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Sätt färgen på den indexerade pixeln till blå
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Tillämpa pixeländringarna på bilden
        image.SavePixels(image.Bounds, pixels);

        // spara alla ändringar.
        image.Save();
    }

    //Skriv MemoryStream till fil
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Se även

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


