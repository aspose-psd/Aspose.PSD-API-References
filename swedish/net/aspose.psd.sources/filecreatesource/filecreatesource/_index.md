---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD för .NET API-referens
description: FileCreateSource byggare. Initierar en ny instans avFileCreateSource class.
type: docs
weight: 10
url: /sv/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initierar en ny instans av[`FileCreateSource`](../) class.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att skapa. |

### Exempel

Det här exemplet skapar en ny bildfil på någon diskplats som specificeras av Source-egenskapen för BmpOptions-instansen. Om den andra parametern inte skickas till FileCreateSources konstruktor, har filen som ska skapas som standard egenskapen IsTemporal satt till True. Med IsTemporal satt till True, kommer ingen fil att sparas på disken i slutet av körningen.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Skapar en instans av PsdOptions och ställer in dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av PsdOptions
//Om den andra parametern inte skickas, har filen som standard IsTemporal satt till True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Skapar en instans av bild 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //gör lite bildbehandling
}
```

### Se även

* class [FileCreateSource](../)
* namnutrymme [Aspose.PSD.Sources](../../filecreatesource/)
* hopsättning [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initierar en ny instans av[`FileCreateSource`](../) class.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att skapa. |
| isTemporal | Boolean | Om inställt på`Sann` den skapade filen kommer att vara tidsmässig. |

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

* class [FileCreateSource](../)
* namnutrymme [Aspose.PSD.Sources](../../filecreatesource/)
* hopsättning [Aspose.PSD](../../../)


