---
title: StreamSource.StreamSource
second_title: Aspose.PSD för .NET API-referens
description: StreamSource byggare. Initierar en ny instans avStreamSource class.
type: docs
weight: 10
url: /sv/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Initierar en ny instans av[`StreamSource`](../) class.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att öppna. |

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

* class [StreamSource](../)
* namnutrymme [Aspose.PSD.Sources](../../streamsource/)
* hopsättning [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initierar en ny instans av[`StreamSource`](../) class.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att öppna. |
| disposeStream | Boolean | om inställt på`Sann` strömmen kommer att avyttras. |

### Exempel

Det här exemplet visar användningen av System.IO.Stream för att skapa en ny bildfil

```csharp
[C#]

//Skapar en instans av PsdOptions och ställer in dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definiera källegenskapen för instansen av PsdOptions
//Den andra booleska parametern bestämmer om strömmen kasseras när den kommit utanför räckvidden
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Skapar en instans av Image and call Create-metoden med PsdOptions som parameter för att initiera Image-objektet   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //gör lite bildbehandling
}
```

### Se även

* class [StreamSource](../)
* namnutrymme [Aspose.PSD.Sources](../../streamsource/)
* hopsättning [Aspose.PSD](../../../)


