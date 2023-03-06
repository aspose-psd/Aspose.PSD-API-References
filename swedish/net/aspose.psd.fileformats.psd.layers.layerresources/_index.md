---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD för .NET API-referens
description: Namnutrymmet innehåller PSDfilformatenheter som finns i lager.
type: docs
weight: 270
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/
---
Namnutrymmet innehåller PSD-filformatenheter som finns i lager.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Basklass för justeringslagerresurser |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | Avsnittet med animerade data. |
| [BlncResource](./blncresource/) | BlncResource-klassen är en resurs av Color Adjustment Layer. |
| [BlwhResource](./blwhresource/) | BlwhResource-klassen är en resurs av svartvitt justeringslager. |
| [BooleanResource](./booleanresource/) | Klass BooleanResource. Det är en pseudo-resurs. Photoshop har det inte |
| [BritResource](./britresource/) | Klass BritResource. Resurs för ljusstyrka/kontrastjustering Layer |
| [CgEdResource](./cgedresource/) | Klass CgEdResource. Content Generator Extra Data (Photoshop CS5) |
| [ClassID](./classid/) | PSD Class ID-objektet. |
| [ClblResource](./clblresource/) | Klass ClblResource. Denna resurs innehåller information om blandning av klippt element. |
| [CmlsResource](./cmlsresource/) | Klass CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) har 6 färgintervall där du kan ändra HSV-parametrar. Varje område har 4 nyckelpunkter för att identifiera områdesgränser. Och det är ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Manager for Curves Adjustment Layer som manipulerar curves |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Manager for Curves Adjustment Layer som manipulerar pixlars map |
| [CurvesManager](./curvesmanager/) | Basklass för att hantera CurvResource |
| [CurvResource](./curvresource/) | Klass CurvResource. Resurs för kurvjustering Layer 1 byte - 0 om kurvor används, 1 om använda pixlar på map om 0 då: 2 byte - kort. Standard är 1 4 byte - int. Används endast sista byte för bit. Första biten är för 1 kanal, den fjärde biten för 4 kanal till exempel 2 byte - korta punkter count 4 bytes * antal punkt - punkter på kurva 2 kort: första positionen, andra höjd 4 byte - ordet "Crv " 2 bytes - kort standard är 4 för Curves 4 byte - int. Standard är 1 4 byte - antal poäng 4 bytes * antal poäng - punkter i kurva 2 kort: första position, andra höjd 0-4 byte - Ledande att vikas för fyra om 1 sedan: 2 bytes - kort. Standard är 1 4 byte - int. Används endast sista byten. En kanal är i en bit. Första biten är för 1 kanal, den fjärde biten för 4 kanaler till exempel 256 * antal ändrade kanaler - ordnade värden för kanalen i intervallet 0 - 255 4 byte - ordet "Crv " 2 byte - kort. Standard är 3 för pixlar på map 4 byte - int Channel count (2 + 256) byte - kort 2 för kanalindex, 256 är ordnade värden för kanal i intervallet 0 - 255 |
| [CustResource](./custresource/) | Class CustResource. Denna resurs innehåller information om blandning av klippt element. |
| [ExpaResource](./exparesource/) | Klass ExpaResource. Resurs för exponeringsjustering Layer |
| [FillLayerResource](./filllayerresource/) | Basklass för fylllagerresurser |
| [FilterEffectMaskData](./filtereffectmaskdata/) | Filtermaskens dataklass. |
| [FXidResource](./fxidresource/) | Filtereffektresursen innehåller kanaler, en användarmask och en arkmask för det smarta filtret. |
| [FxrpResource](./fxrpresource/) | Klass FxrpResource. Referenspunkten för layer |
| [GdFlResource](./gdflresource/) | Klass GdFlResource. Denna resurs innehåller information om blandning av klippt element. |
| [Hue2Resource](./hue2resource/) | Klass Hue2Resource. Resurs för exponeringsjustering Layer |
| [InfxResource](./infxresource/) | Klass InfxResource. Denna resurs innehåller information om blandning av klippt element. |
| [IopaResource](./ioparesource/) | Klass IopaResource. Den här resursen innehåller information om egenskapen fill opacity från lagerstilen form |
| [KnkoResource](./knkoresource/) | Klass KnkoResource. Denna resurs innehåller information om blandning av klippt element. |
| [LayerSectionResource](./layersectionresource/) | Lagersektionsresursen. |
| [LclrResource](./lclrresource/) | Klass LclrResource. Denna resurs innehåller information om färgen på lagret i lagerlistan är PS. Det är bara |
| [LevelChannel](./levelchannel/) | Klass för att arbeta med kanaler i Levels Adjustment Layer |
| [LevlResource](./levlresource/) | KlassnivåResurs. Resurs för exponeringsjustering Layer |
| [Lfx2Resource](./lfx2resource/) | Lfx2 resurs (effektresurs) |
| [LiFdDataSource](./lifddatasource/) | Definierar liFD-datakällklassen i PSD File som innehåller information om en inbäddad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop® files |
| [LiFeDataSource](./lifedatasource/) | Definierar klassen LnkeDataSource som innehåller information om extern länkad fil. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop® files |
| [LinkDataSource](./linkdatasource/) | Definierar klassen LinkDataSource som innehåller information om en länkad fil eller en tillgång i PSD-filen. |
| [LinkResource](./linkresource/) | Definierar klassen LinkResource som innehåller information om länkade eller inbäddade filer i PSD-formatbilden. Länkresursen kan innehålla flera[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instanser som kan nås av indexerare i vilken som helst härledd klass. |
| [Lnk2Resource](./lnk2resource/) | Definierar klassen som innehåller information om inbäddade filer i PSD-formatbilden. Länkresursen kan innehålla flera[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instanser som kan nås av indexeraren. |
| [Lnk3Resource](./lnk3resource/) | Definierar klassen som innehåller information om en inbäddad fil i PSD-formatet 32 bitar per kanalbild. Länkresursen kan innehålla flera[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instanser som kan nås av indexer. |
| [LnkeResource](./lnkeresource/) | Definierar klassen LnkeResource som innehåller information om externa länkade filer eller tillgångar i PSD-formatbilden. Länkresursen kan innehålla flera[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instanser som kan nås av indexer. Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop®-filer programmatiskt |
| [LnsrResource](./lnsrresource/) | Klass lnsrResource. |
| [Lr16Resource](./lr16resource/) | lr32-resursen. |
| [Lr32Resource](./lr32resource/) | lr32-resursen. |
| [LspfResource](./lspfresource/) | Lagerskyddade inställningar |
| [LuniResource](./luniresource/) | Lagernamn resurs |
| [LyidResource](./lyidresource/) | Klass LyidResource. |
| [MixrResource](./mixrresource/) | Klass MixrResource. Resurs för Channel Mixer Adjustment Layer |
| [MlstResource](./mlstresource/) | Mlst-resursen. Den här klassen innehåller bland annat information om lagrets position på tidslinjen. |
| [NvrtResource](./nvrtresource/) | Klass NvrtResource. Resurs för Invertera justeringslager. |
| [OSTypeStructure](./ostypestructure/) | Representerar OS-typstrukturen. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Representerar[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resursregistret. |
| [PattResource](./pattresource/) | Klass PattResource. Resurs med mönsterdata |
| [PattResourceData](./pattresourcedata/) | Klassen att lagra mönsterdata för[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resurs. |
| [PhflResource](./phflresource/) | Klass PhflResource. Resurs för exponeringsjustering Layer 2 Version ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ-färg(Endast i version 3) 10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (endast 2) 4 Density 1 Bevara ljusstyrkan |
| [PhflResourceVersion2](./phflresourceversion2/) | Klass PhflResource. Resurs för exponeringsjustering Layer 2 Version ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ-färg(Endast i version 3) 10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (endast 2) 4 Density 1 Bevara ljusstyrkan |
| [PhflResourceVersion3](./phflresourceversion3/) | Klass PhflResource. Resurs för exponeringsjustering Layer 2 Version ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ-färg(Endast i version 3) 10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (endast 2) 4 Density 1 Bevara ljusstyrkan |
| [PlacedResource](./placedresource/) | Definierar klassen PlacedResource som innehåller vanlig information om ett placerat lager eller ett smart objektlager i PSD-filen. Is används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna. |
| [PlLdResource](./plldresource/) | Definierar klassen PlLdResource som innehåller information om ett placerat lager i PSD-filen. Is används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna. Den ersattes av SoLdResource i Adobe® Photoshop® CS3 |
| [PostResource](./postresource/) | Klass PostResource. Posterize lagerinställningar. |
| [PtFlResource](./ptflresource/) | Klass PtFlResource. Innehåller mönsterfyllningslagerdata. |
| [ShmdResource](./shmdresource/) | Klass ShmdResource. Metadatainställningar |
| [SmartObjectResource](./smartobjectresource/) | Definierar klassen SmartObjectResource som innehåller information om ett smart objektlager i en PSD-fil. Is är basklassen för Sold och Sole-resurser som används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna. |
| [SmartResourceCreator](./smartresourcecreator/) | Definierar klassen SmartResourceCreator som kan skapa PlLd-, SoLd- och SoLe-resurser. Is används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna. |
| [SoCoResource](./socoresource/) | Class SoCoResource. Den här resursen innehåller information om Color Fill Layers |
| [SoLdResource](./soldresource/) | Definierar klassen SoLdResource som innehåller information om ett smart objektlager i en PSD-fil. Is används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna. |
| [SoLeResource](./soleresource/) | Definierar klassen SoLeResource som innehåller information om ett smart objektlager i en PSD-fil. Is används för att stödja smarta objektlager med externa fillänkar i Adobe® Photoshop®-bilderna. |
| [Txt2Resource](./txt2resource/) | Txt2 resursklass |
| [TypeToolFontInfo](./typetoolfontinfo/) | Innehåller information om typverktygets typsnitt. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | Typverktygsinformationen. För PSD-version högre eller lika med 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | Typverktygsinformationen. För PSD-version lägre än 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Skriv verktygslinjeinfo. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Skriv information om verktygsstil. |
| [UnknownResource](./unknownresource/) | Den okända resursen. |
| [VectorPathDataResource](./vectorpathdataresource/) | Klass VectorPathDataResource. Den här resursen innehåller information om vektorlager mask |
| [VibAResource](./vibaresource/) | VibA Resource. |
| [VmskResource](./vmskresource/) | Klass VmskResource. Den här resursen innehåller information om vektorlager mask |
| [VogkResource](./vogkresource/) | Dataresursen för vektoruppkomst. |
| [VsmsResource](./vsmsresource/) | Klass VsmsResource. Denna resurs innehåller information om vektorlager mask |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | Den[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resurs laddare. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Definierar IPlacedLayerResource-gränssnittet som innehåller information om ett placerat lager i PSD-filen. Is är ett uppmärkningsgränssnitt som används för att ange PlLd, Sold och Sole-resurser i Adobe® Photoshop®-bilderna. Is används för att stödja smarta objektlager i Adobe® Photoshop®-bilderna. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Definierar ISmartObjectLayerResource-gränssnittet som innehåller information om en smart objektlagerresurs i PSD-filen. Is är också ett uppmärkningsgränssnitt som används för att ange både sålda och enda resurser i Adobe® Photoshop®-bilderna. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Alternativ för lagerlås |
| [LayerSectionSubtype](./layersectionsubtype/) | Sektionens undertyp |
| [LayerSectionType](./layersectiontype/) | Lagersektionen type |
| [LinkDataSourceType](./linkdatasourcetype/) | Definierar LinkDataSourceType-uppräkningen för datakällorna i PSD-länkresursen. |
| [LnsrResourceType](./lnsrresourcetype/) | Upptäckte möjliga Lnsr-resurstyper |
| [PlacedLayerType](./placedlayertype/) | Definierar PlacedLayerType-uppräkningen för det placerade lagret PlLd-resursen. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Möjliga färger för arkets färginställning. Det är gränssnittets dekorativa färg på lager i lagers lista i PS |


