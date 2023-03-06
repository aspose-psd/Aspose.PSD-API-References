---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD voor .NET API-referentie
description: FileCreateSource constructeur. Initialiseert een nieuw exemplaar van hetFileCreateSource klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initialiseert een nieuw exemplaar van het[`FileCreateSource`](../) klasse.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad dat moet worden gemaakt. |

### Voorbeelden

In dit voorbeeld wordt een nieuw afbeeldingsbestand gemaakt op een bepaalde schijflocatie, zoals gespecificeerd door de eigenschap Source van de instantie BmpOptions. Als de tweede parameter niet wordt doorgegeven aan de constructor van FileCreateSource, heeft het te maken bestand standaard de eigenschap IsTemporal ingesteld op True. Als IsTemporal is ingesteld op True, wordt aan het einde van de uitvoering geen bestand op schijf opgeslagen.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Maakt een instantie van PsdOptions en stelt de verschillende eigenschappen ervan in
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Maak een instantie van FileCreateSource en wijs deze toe als bron voor de instantie van PsdOptions
//Als de tweede parameter niet wordt doorgegeven, is IsTemporal standaard ingesteld op True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Maakt een exemplaar van Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // doe wat beeldverwerking
}
```

### Zie ook

* class [FileCreateSource](../)
* naamruimte [Aspose.PSD.Sources](../../filecreatesource/)
* montage [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`FileCreateSource`](../) klasse.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad dat moet worden gemaakt. |
| isTemporal | Boolean | Indien ingesteld op`WAAR` het aangemaakte bestand zal tijdelijk zijn. |

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

* class [FileCreateSource](../)
* naamruimte [Aspose.PSD.Sources](../../filecreatesource/)
* montage [Aspose.PSD](../../../)


