---
title: Class LiFdDataSource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource klass. Definierar liFDdatakällklassen i PSD File som innehåller information om en inbäddad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe Photoshop files
type: docs
weight: 2670
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
## LiFdDataSource class

Definierar liFD-datakällklassen i PSD File som innehåller information om en inbäddad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop® files

```csharp
public class LiFdDataSource : LinkDataSource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | Initierar en ny instans av`LiFdDataSource` class. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | Initierar en ny instans av`LiFdDataSource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om PSD-tillgången är låst. Tillståndet för tillgången är låst, för Adobe® Photoshop® СС Libraries-tillgångar. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Hämtar eller ställer in tillgångens modifierade tid, för Adobe® Photoshop® СС Libraries-tillgångar. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Hämtar eller ställer in den underordnade dokumentidentifieraren i livs- eller liFD-datakällan för Lnk2 / LnkE Adobe® Photoshop®-resursen. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Hämtar eller ställer in ID för den för närvarande valda komp för det underordnade dokumentet, vilket kommer att vara -1 om ingen är vald. Comps är sammansättningar av en sidlayout som designers kan skapa. Med hjälp av lagersammansättningar kan du skapa, hantera och visa flera versioner av en layout i en enda Adobe® Photoshop®-fil. En lagerkomp är en ögonblicksbild av ett tillstånd på panelen Lager. Layer Comps sparar tre typer av lageralternativ men den här egenskapen får Layer Comp-urvalsidentifieraren för smarta objekt. [Layer comps i Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | Hämtar eller ställer in data för inbäddade smarta objekt i PSD-fil. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Hämtar eller ställer in filskaparen i PSD-formatet LnkE / Lnk2 resurs. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Hämtar eller ställer in typen av inbäddad eller extern fil som Adobe® Photoshop® Lnk2 / LnkE-resursen innehåller eller länkar. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna länkdatakälla har filen öppen deskriptor: CompId och OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Får ett värde som anger om denna PSD-länkdatakälla länkar till Adobe® Photoshop® СС Library-objektet. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Hämtar länkdatakällans längd i byte. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Hämtar det ursprungliga ID:t för den för närvarande valda Comp för det underordnade dokumentet, vilket kommer att vara -1 om ingen har valts. Den här egenskapen får den ursprungliga lager Comp-urvalsidentifieraren för Smart Objects. [Layer comps i Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Hämtar det ursprungliga filnamnet för datakällan i Adobe® Photoshop® globala länkresurs. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Hämtar Adobe® Photoshop® global länkdatakälla som kan vara en av följande eller ingen: Den inbäddade länkade filen liFD som motsvarar PSD:n Lnk2Resource Den externa länkade filens livslängd som motsvarar PSD Linked Resourcealias The linked |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Hämtar den globala unika identifieraren för datakällan i PSD-länkresursen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Hämtar versionen av datakällan i PSD LnkE / Lnk2-resursen. |

### Se även

* class [LinkDataSource](../linkdatasource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


