---
title: "Klass LiFdDataSource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource-klass. Definierar liFD-datakällklassen i PSD‑filen som innehåller information om en inbäddad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe Photoshop‑filer."
type: docs
weight: 2970
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
{{< psd/tize >}}
## LiFdDataSource class

Definierar liFD-datakällklassen i PSD‑fil som innehåller information om en inbäddad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop®‑filer.

```csharp
public class LiFdDataSource : LinkDataSource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | Initierar en ny instans av klassen `LiFdDataSource`. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | Initierar en ny instans av klassen `LiFdDataSource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Hämtar eller anger ett värde som indikerar om PSD‑tillgången är låst. Tillgångens låsta status, för Adobe® Photoshop® CC Libraries‑tillgångar. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Hämtar eller anger den modifierade tiden för tillgången, för Adobe® Photoshop® CC Libraries‑tillgångar. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Hämtar eller anger identifieraren för underdokumentet i liFE- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Hämtar eller anger ID för den för närvarande valda kompositionen för underdokumentet, vilket blir -1 om ingen är vald. Kompositioner (comps) är sammansättningar av en sidlayout som designers kan skapa. Med lager‑kompositioner kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe® Photoshop®-fil. En lager‑komposition är en ögonblicksbild av ett tillstånd i lagerpanelen. Lager‑kompositioner sparar tre typer av lageralternativ men den här egenskapen hämtar identifieraren för lager‑kompositionsvalet för Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | Hämtar eller anger den inbäddade smartobjektsdata i PSD‑filen. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Hämtar eller anger filskaparen i PSD-formatets LnkE / Lnk2‑resurs. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Hämtar eller anger typen av den inbäddade eller externa filen som Adobe® Photoshop® Lnk2 / LnkE‑resursen innehåller eller länkar till. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Hämtar eller anger ett värde som indikerar om denna länkdatas källa har filens öppna beskrivare: CompId och OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Hämtar ett värde som indikerar om denna PSD‑länkdatas källa länkar till Adobe® Photoshop® CC Library‑objektet. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Hämtar länkdatas källa längd i byte. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Hämtar det ursprungliga ID:t för den för närvarande valda kompositionen för underdokumentet, vilket blir -1 om ingen är vald. Denna egenskap hämtar den ursprungliga lager‑kompositionsidentifieraren för Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® global länkretsurs. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Hämtar Adobe® Photoshop® globala länkdatakälltyp som kan vara någon av följande eller ingen: Den inbäddade länkade filen liFD som motsvarar PSD Lnk2Resource Den externa länkade filen liFE som motsvarar PSD LnkeResource Den länkade filaliasen liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Hämtar den globala unika identifieraren för datakällan i PSD-länkresursen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Hämtar versionen av datakällan i PSD LnkE / Lnk2-resursen. |

### Se även

* class [LinkDataSource](../linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


