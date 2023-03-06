---
title: StreamSource.StreamSource
second_title: Aspose.PSD voor .NET API-referentie
description: StreamSource constructeur. Initialiseert een nieuw exemplaar van hetStreamSource klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Initialiseert een nieuw exemplaar van het[`StreamSource`](../) klasse.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom om te openen. |

### Voorbeelden

Dit voorbeeld laat zien hoe Pixel-informatie in een array van typekleur wordt geladen, de array wordt gemanipuleerd en teruggezet naar de afbeelding. Om deze bewerkingen uit te voeren, maakt dit voorbeeld een nieuw afbeeldingsbestand (in PSD-indeling) met behulp van het MemoryStream-object.

```csharp
[C#]

//Maak een exemplaar van MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // Maak een instantie van PsdOptions en stel de verschillende eigenschappen in, inclusief de eigenschap Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Maak een exemplaar van Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // Haal de pixels van de afbeelding op door het gebied op te geven als afbeeldingsgrens
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loop over de array en stel de kleur in van de alternatieve geïndexeerde pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // Stel de geïndexeerde pixelkleur in op geel
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                // Stel de geïndexeerde pixelkleur in op blauw
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Pas de pixelwijzigingen toe op de afbeelding
        image.SavePixels(image.Bounds, pixels);

        // sla alle veranderingen op.
        image.Save();
    }

    // Schrijf MemoryStream naar bestand
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Zie ook

* class [StreamSource](../)
* naamruimte [Aspose.PSD.Sources](../../streamsource/)
* montage [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`StreamSource`](../) klasse.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom om te openen. |
| disposeStream | Boolean | indien ingesteld op`WAAR` de stroom zal worden afgevoerd. |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van System.IO.Stream om een nieuw afbeeldingsbestand te maken

```csharp
[C#]

//Maakt een instantie van PsdOptions en stelt de verschillende eigenschappen ervan in
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Maak een exemplaar van System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definieer de broneigenschap voor de instantie van PsdOptions
// Tweede booleaanse parameter bepaalt of de stream wordt verwijderd zodra deze buiten bereik is
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Maakt een instantie van Image en roept de Create-methode aan met PsdOptions als parameter om het Image-object te initialiseren   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // doe wat beeldverwerking
}
```

### Zie ook

* class [StreamSource](../)
* naamruimte [Aspose.PSD.Sources](../../streamsource/)
* montage [Aspose.PSD](../../../)


