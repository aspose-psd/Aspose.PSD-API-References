---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FileCreateSource konstruktor. Initierar en ny instans av klassen FileCreateSource"
type: docs
weight: 10
url: /sv/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Initierar en ny instans av klassen [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen att skapa. |

## Exempel

Det här exemplet skapar en ny Image‑fil på en viss diskplats enligt Source‑egenskapen i BmpOptions‑instansen. Om den andra parametern inte skickas till konstruktorn för FileCreateSource, får den fil som ska skapas som standard egenskapen IsTemporal satt till True. När IsTemporal är satt till True sparas ingen fil på disken när körningen avslutas.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Skapar en instans av PsdOptions och anger dess olika egenskaper.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av FileCreateSource och tilldela den som Source för instansen av PsdOptions
//Om den andra parametern inte skickas, får filen som standard egenskapen IsTemporal satt till True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Skapar en instans av Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //utför någon bildbehandling
}
```

### Se även

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initierar en ny instans av klassen [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen att skapa. |
| isTemporal | Boolean | Om den är satt till `true` kommer den skapade filen att vara temporär. |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


