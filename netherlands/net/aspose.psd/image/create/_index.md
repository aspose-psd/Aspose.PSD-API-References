---
title: Image.Create
second_title: Aspose.PSD voor .NET API-referentie
description: Image methode. Maakt een nieuwe afbeelding met de opgegeven aanmaakopties.
type: docs
weight: 10
url: /nl/net/aspose.psd/image/create/
---
## Image.Create method

Maakt een nieuwe afbeelding met de opgegeven aanmaakopties.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | De afbeeldingsopties. |
| width | Int32 | De breedte. |
| height | Int32 | De hoogte. |

### Winstwaarde

De nieuw gemaakte afbeelding.

### Voorbeelden

In dit voorbeeld wordt een nieuw afbeeldingsbestand gemaakt op een bepaalde schijflocatie, zoals gespecificeerd door de eigenschap Source van de instantie PsdOptions. Verschillende eigenschappen voor de PsdOptions-instantie worden ingesteld voordat de eigenlijke afbeelding wordt gemaakt. Vooral de eigenschap Source, die in dit geval verwijst naar de daadwerkelijke schijflocatie.

```csharp
[C#]

//Maak een instantie van PsdOptions en stel de verschillende eigenschappen in
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Maak een instantie van FileCreateSource en wijs deze toe als bron voor de instantie van PsdOptions
//De tweede Booleaanse parameter bepaalt of het aan te maken bestand IsTemporal is of niet
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Maak een exemplaar van Image en initialiseer het met een exemplaar van PsdOptions door de Create-methode aan te roepen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // doe wat beeldverwerking

    // sla alle veranderingen op
    image.Save();
}
```

### Zie ook

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)


