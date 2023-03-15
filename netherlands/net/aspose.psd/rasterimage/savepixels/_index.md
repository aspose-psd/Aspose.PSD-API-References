---
title: RasterImage.SavePixels
second_title: Aspose.PSD voor .NET API-referentie
description: RasterImage methode. Slaat de pixels op.
type: docs
weight: 520
url: /nl/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Slaat de pixels op.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | Rectangle | De rechthoek om pixels in op te slaan. |
| pixels | Color[] | De pixelarray. |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* naamruimte [Aspose.PSD](../../rasterimage/)
* montage [Aspose.PSD](../../../)


