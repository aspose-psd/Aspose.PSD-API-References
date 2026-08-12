---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "StreamSource konstruktor. Initierar en ny instans av StreamSource-klassen"
type: docs
weight: 10
url: /sv/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Initierar en ny instans av [`StreamSource`](../)-klassen.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen att öppna. |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initierar en ny instans av [`StreamSource`](../)-klassen.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen att öppna. |
| disposeStream | Boolean | Om den är satt till `true` kommer strömmen att disponeras. |

## Exempel

Detta exempel visar hur man använder System.IO.Stream för att skapa en ny bildfil.

```csharp
[C#]

//Skapar en instans av PsdOptions och anger dess olika egenskaper.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definiera käll‑egenskapen för instansen av PsdOptions.
//Andra boolska parametern bestämmer om Streamen avyttras när den lämnar scopet.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Skapar en instans av Image och anropar Create‑metoden med PsdOptions som parameter för att initiera Image‑objektet.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //utför någon bildbehandling
}
```

### Se även

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


