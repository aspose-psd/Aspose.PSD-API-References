---
title: RasterImage.SavePixels
second_title: Aspose.PSD för .NET API-referens
description: RasterImage metod. Sparar pixlarna.
type: docs
weight: 520
url: /sv/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Sparar pixlarna.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln att spara pixlar till. |
| pixels | Color[] | Pixelarrayen. |

### Exempel

Det här exemplet visar hur man laddar pixelinformation i en array av typfärg, manipulerar arrayen och återställer den till bilden. För att utföra dessa operationer skapar det här exemplet en ny bildfil (i PSD-format) med MemoryStream-objekt.

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av PsdOptions och ställ in dess olika egenskaper inklusive egenskapen Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Skapa en instans av bild
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Hämta pixlarna i bilden genom att ange området som bildgräns
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Slinga över Arrayen och ställer in färgen på alrenativt indexerad pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ställ in den indexerade pixelfärgen till gul
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Ställ in den indexerade pixelfärgen till blå
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
* namnutrymme [Aspose.PSD](../../rasterimage/)
* hopsättning [Aspose.PSD](../../../)


