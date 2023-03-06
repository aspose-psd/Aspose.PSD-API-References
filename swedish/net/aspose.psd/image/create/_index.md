---
title: Image.Create
second_title: Aspose.PSD för .NET API-referens
description: Image metod. Skapar en ny bild med de angivna skapaalternativen.
type: docs
weight: 10
url: /sv/net/aspose.psd/image/create/
---
## Image.Create method

Skapar en ny bild med de angivna skapaalternativen.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Bildalternativen. |
| width | Int32 | Bredden. |
| height | Int32 | Höjden. |

### Returvärde

Den nyskapade bilden.

### Exempel

Det här exemplet skapar en ny bildfil på någon diskplats som specificeras av Source-egenskapen för PsdOptions-instansen. Flera egenskaper för PsdOptions-instansen ställs in innan den faktiska bilden skapas. Speciellt egenskapen Source, som refererar till den faktiska diskplatsen i det här fallet.

```csharp
[C#]

//Skapa en instans av PsdOptions och ställ in dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av PsdOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Skapa en instans av bild och initiera den med instans av PsdOptions genom att anropa metoden Skapa
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //gör lite bildbehandling

    // spara alla ändringar
    image.Save();
}
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)


