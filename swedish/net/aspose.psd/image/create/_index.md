---
title: "Image.Create"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Image‑metod. Skapar en ny bild med de angivna skapalternativen"
type: docs
weight: 10
url: /sv/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Skapar en ny bild med de angivna skapalternativen.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Bildalternativen. |
| bredd | Int32 | Bredden. |
| höjd | Int32 | Höjden. |

### Returvärde

Den nyss skapade bilden.

## Exempel

Detta exempel skapar en ny bildfil på en viss diskplats enligt Source‑egenskapen i PsdOptions‑instansen. Flera egenskaper för PsdOptions‑instansen sätts innan den faktiska bilden skapas. Speciellt Source‑egenskapen, som i detta fall refererar till den faktiska diskplatsen.

```csharp
[C#]

//Skapa en instans av PsdOptions och ange dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av FileCreateSource och tilldela den som Source för instansen av PsdOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Skapa en instans av Image och initiera den med en instans av PsdOptions genom att anropa Create‑metoden
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //utför någon bildbehandling

    // spara alla ändringar
    image.Save();
}
```

### Se även

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


