---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD voor .NET API-referentie
description: De naamruimte bevat entiteiten in PSDbestandsindeling in lagen.
type: docs
weight: 270
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/
---
De naamruimte bevat entiteiten in PSD-bestandsindeling in lagen.

## Klassen

| Klas | Beschrijving |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Basisklasse voor aanpassingslaag resources |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | De sectie met geanimeerde gegevens. |
| [BlncResource](./blncresource/) | BlncResource-klasse is een bron van Color Adjustment Layer. |
| [BlwhResource](./blwhresource/) | BlwhResource-klasse is een bron van Black and White Adjustment Layer. |
| [BooleanResource](./booleanresource/) | Klasse BooleanResource. Het is een pseudobron. Photoshop heeft het niet |
| [BritResource](./britresource/) | Klasse BritResource. Hulpbron voor aanpassing van helderheid/contrast Layer |
| [CgEdResource](./cgedresource/) | Klasse CgEdResource. Inhoudsgenerator Extra gegevens (Photoshop CS5) |
| [ClassID](./classid/) | Het PSD Class ID-object. |
| [ClblResource](./clblresource/) | Klasse ClblResource. Deze bron bevat informatie over het overvloeien van geknipte elementen. |
| [CmlsResource](./cmlsresource/) | Klasse CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) heeft 6 kleurbereiken waar u HSV-parameters kunt wijzigen. Elk bereik heeft 4 belangrijke punten om bereikgrenzen te identificeren. En het is ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Beheerder voor curvenaanpassingslaag die curven manipuleert |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Beheerder voor curvenaanpassingslaag die de kaart van pixels manipuleert |
| [CurvesManager](./curvesmanager/) | Basisklasse om CurvResource te beheren |
| [CurvResource](./curvresource/) | Klasse CurvResource. Bron van aanpassing van curven Layer 1 byte - 0 als curven worden gebruikt, 1 als pixels op kaart worden gebruikt als 0 dan: 2 bytes - kort. Standaard is 1 4 bytes - int. Alleen laatste byte voor bit gebruikt. Eerste bit is voor 1 kanaal, het vierde bit voor 4 kanalen bijvoorbeeld 2 bytes - korte punten count 4 bytes * aantal punten - punten van curve 2 kort: eerste positie, tweede hoogte 4 bytes - woord "Crv " 2 bytes - korte standaard is 4 voor Curves 4 bytes - int. Standaard is 1 4 bytes - aantal punten 4 bytes * aantal punten - punten van curve 2 kort: eerste positie, tweede hoogte 0-4 bytes - leidend tot vouw voor vier als 1 dan: 2 bytes - kort. Standaard is 1 4 bytes - int. Alleen de laatste byte gebruikt. Eén kanaal is in één bit. Eerste bit is voor 1 kanaal, het vierde bit voor 4 kanalen bijvoorbeeld 256 * aantal gewijzigde kanalen - geordende waarden van kanaal in bereik 0 - 255 4 bytes - woord "Crv " 2 bytes - kort. Standaard is 3 voor pixels op map 4 bytes - int Channel count (2 + 256) bytes - kort 2 voor kanaalindex, 256 is geordende waarden van kanaal in bereik 0 - 255 |
| [CustResource](./custresource/) | Klasse CustResource. Deze bron bevat informatie over het overvloeien van geknipte elementen. |
| [ExpaResource](./exparesource/) | Klasse ExpaResource. Hulpbron voor belichtingsaanpassing Layer |
| [FillLayerResource](./filllayerresource/) | Basisklasse voor bronnen opvullaag |
| [FilterEffectMaskData](./filtereffectmaskdata/) | De gegevensklasse van het filtermasker. |
| [FXidResource](./fxidresource/) | De bron Filtereffecten bevat kanalen, een gebruikersmasker en een bladmasker voor het slimme filter. |
| [FxrpResource](./fxrpresource/) | Klasse FxrpResource. Het referentiepunt van layer |
| [GdFlResource](./gdflresource/) | Klasse GdFlResource. Deze bron bevat informatie over het overvloeien van geknipte elementen. |
| [Hue2Resource](./hue2resource/) | Klasse Hue2Resource. Hulpbron voor belichtingsaanpassing Layer |
| [InfxResource](./infxresource/) | Klasse InfxResource. Deze bron bevat informatie over het overvloeien van geknipte elementen. |
| [IopaResource](./ioparesource/) | Klasse IopaResource. Deze bron bevat informatie over de eigenschap opvuldekking van de laagstijl form |
| [KnkoResource](./knkoresource/) | Klasse KnkoResource. Deze bron bevat informatie over het overvloeien van geknipte elementen. |
| [LayerSectionResource](./layersectionresource/) | De bron van de laagsectie. |
| [LclrResource](./lclrresource/) | Klasse LclrResource. Deze bron bevat informatie over de kleur van de laag in de lagenlijst is PS. Het is slechts |
| [LevelChannel](./levelchannel/) | Klasse voor het werken met kanalen in Levels Adjustment Layer |
| [LevlResource](./levlresource/) | Klasse LevlResource. Hulpbron voor belichtingsaanpassing Layer |
| [Lfx2Resource](./lfx2resource/) | Lfx2 bron (effectbron) |
| [LiFdDataSource](./lifddatasource/) | Definieert de liFD-gegevensbronklasse in het PSD-bestand die informatie bevat over een ingesloten bestand. Dit maakt deel uit van de PSD-bestandsindelingsmanipulatie-API die helpt bij het wijzigen van Adobe® Photoshop®-bestanden |
| [LiFeDataSource](./lifedatasource/) | Definieert de LnkeDataSource-klasse die informatie bevat over extern gekoppeld bestand. Dit maakt deel uit van de PSD File Format Manipulation API die helpt bij het wijzigen van Adobe® Photoshop®-bestanden |
| [LinkDataSource](./linkdatasource/) | Definieert de klasse LinkDataSource die informatie bevat over een gekoppeld bestand of een asset in het PSD-bestand. |
| [LinkResource](./linkresource/) | Definieert de klasse LinkResource die informatie bevat over gekoppelde of ingesloten bestanden in de afbeelding in PSD-indeling. De linkbron kan meerdere[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instanties die toegankelijk zijn voor indexeerders in elke afgeleide klasse. |
| [Lnk2Resource](./lnk2resource/) | Definieert de klasse die informatie bevat over ingesloten bestanden in de afbeelding in PSD-indeling. De koppelingsresource kan meerdere[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instanties die toegankelijk zijn voor de indexer. |
| [Lnk3Resource](./lnk3resource/) | Definieert de klasse die informatie bevat over een ingebed bestand in het PSD-formaat 32 bit per kanaalbeeld. De linkbron kan meerdere[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instanties die toegankelijk zijn voor indexer. |
| [LnkeResource](./lnkeresource/) | Definieert de klasse LnkeResource die informatie bevat over externe gekoppelde bestanden of middelen in de afbeelding in PSD-indeling. De koppelingsbron kan meerdere[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instanties die toegankelijk zijn voor indexer. Dit is een onderdeel van de PSD File Format Manipulation API die helpt bij het programmatisch wijzigen van Adobe® Photoshop®-bestanden |
| [LnsrResource](./lnsrresource/) | Klasse lnsrResource. |
| [Lr16Resource](./lr16resource/) | De lr32-resource. |
| [Lr32Resource](./lr32resource/) | De lr32-resource. |
| [LspfResource](./lspfresource/) | Laagbeveiligde instellingen |
| [LuniResource](./luniresource/) | Laagnaam resource |
| [LyidResource](./lyidresource/) | Klasse LyidResource. |
| [MixrResource](./mixrresource/) | Klasse MixrResource. Bron van Channel Mixer Adjustment Layer |
| [MlstResource](./mlstresource/) | De mlst resource. Deze klasse bevat onder andere informatie over de positie van de laag op de tijdlijn. |
| [NvrtResource](./nvrtresource/) | Klasse NvrtResource. Bron van aanpassingslaag omkeren. |
| [OSTypeStructure](./ostypestructure/) | Vertegenwoordigt de OS-typestructuur. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Vertegenwoordigt de[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) bronnenregister. |
| [PattResource](./pattresource/) | Klasse PattResource. Bron met patroon data |
| [PattResourceData](./pattresourcedata/) | De klasse om de patroongegevens voor op te slaan[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) hulpbron. |
| [PhflResource](./phflresource/) | Klasse PhflResource. Bron van belichtingsaanpassingslaag 2 versie (= 3) of (= 2) 12 4 bytes elk voor XYZ-kleur (alleen in versie 3) 10 2 bytes kleurruimte gevolgd door 4 * 2 bytes kleurcomponent (alleen in versie 2) 4 Dichtheid 1 Helderheid behouden |
| [PhflResourceVersion2](./phflresourceversion2/) | Klasse PhflResource. Bron van belichtingsaanpassingslaag 2 versie (= 3) of (= 2) 12 4 bytes elk voor XYZ-kleur (alleen in versie 3) 10 2 bytes kleurruimte gevolgd door 4 * 2 bytes kleurcomponent (alleen in versie 2) 4 Dichtheid 1 Helderheid behouden |
| [PhflResourceVersion3](./phflresourceversion3/) | Klasse PhflResource. Bron van belichtingsaanpassingslaag 2 versie (= 3) of (= 2) 12 4 bytes elk voor XYZ-kleur (alleen in versie 3) 10 2 bytes kleurruimte gevolgd door 4 * 2 bytes kleurcomponent (alleen in versie 2) 4 Dichtheid 1 Helderheid behouden |
| [PlacedResource](./placedresource/) | Definieert de klasse PlacedResource die algemene informatie bevat over een geplaatste laag of een slimme objectlaag in het PSD-bestand. Wordt gebruikt om slimme objectlagen in de Adobe® Photoshop®-afbeeldingen te ondersteunen. |
| [PlLdResource](./plldresource/) | Definieert de PlLdResource-klasse die informatie bevat over een geplaatste laag in het PSD-bestand. Wordt gebruikt om slimme objectlagen in de Adobe® Photoshop®-afbeeldingen te ondersteunen. Het werd vervangen door SoLdResource in de Adobe® Photoshop® CS3 |
| [PostResource](./postresource/) | Klasse PostResource. Laaginstellingen posteriseren. |
| [PtFlResource](./ptflresource/) | Klasse PtFlResource. Bevat patroonvullaaggegevens. |
| [ShmdResource](./shmdresource/) | Klasse ShmdResource. Metadata-instellingen |
| [SmartObjectResource](./smartobjectresource/) | Definieert de SmartObjectResource-klasse die informatie bevat over een slimme objectlaag in een PSD-bestand. Is de basisklasse voor Verkochte en Sole-bronnen die wordt gebruikt om slimme objectlagen in de Adobe® Photoshop®-afbeeldingen te ondersteunen. |
| [SmartResourceCreator](./smartresourcecreator/) | Definieert de SmartResourceCreator-klasse die PlLd-, SoLd- en SoLe-resources kan maken. Wordt gebruikt om slimme objectlagen in de Adobe® Photoshop®-afbeeldingen te ondersteunen. |
| [SoCoResource](./socoresource/) | Klasse SoCoResource. Deze bron bevat informatie over Color Fill Layers |
| [SoLdResource](./soldresource/) | Definieert de SoLdResource-klasse die informatie bevat over een slimme objectlaag in een PSD-bestand. Wordt gebruikt om slimme objectlagen te ondersteunen in de Adobe® Photoshop®-afbeeldingen. |
| [SoLeResource](./soleresource/) | Definieert de SoLeResource-klasse die informatie bevat over een slimme objectlaag in een PSD-bestand. Wordt gebruikt om slimme objectlagen te ondersteunen met externe bestandskoppelingen in de Adobe® Photoshop®-afbeeldingen. |
| [Txt2Resource](./txt2resource/) | Txt2 bronklasse |
| [TypeToolFontInfo](./typetoolfontinfo/) | Bevat informatie over het lettertype van het typegereedschap. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | De informatie over het type gereedschap. Voor PSD-versie hoger of gelijk aan 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | De informatie over het type gereedschap. Voor PSD-versie lager dan 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Type gereedschapsregel info. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Typ informatie over gereedschapsstijl. |
| [UnknownResource](./unknownresource/) | De onbekende bron. |
| [VectorPathDataResource](./vectorpathdataresource/) | Klasse VectorPathDataResource. Deze bron bevat informatie over vectorlaagmasker |
| [VibAResource](./vibaresource/) | VibA-bron. |
| [VmskResource](./vmskresource/) | Klasse VmskResource. Deze bron bevat informatie over vectorlaagmasker |
| [VogkResource](./vogkresource/) | De gegevensbron voor het ontstaan van vectoren. |
| [VsmsResource](./vsmsresource/) | Klasse VsmsResource. Deze bron bevat informatie over vectorlaagmasker |
## Interfaces

| Koppel | Beschrijving |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | De[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) bronlader. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Definieert de IPlacedLayerResource-interface die informatie bevat over een geplaatste laag in het PSD-bestand. Is is een markup-interface die wordt gebruikt om PlLd-, Sold- en Sole-bronnen aan te duiden in de Adobe® Photoshop®-afbeeldingen. Is wordt gebruikt om slimme objectlagen in de Adobe® Photoshop®-afbeeldingen. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Definieert de ISmartObjectLayerResource-interface die informatie bevat over een slimme objectlaagbron in het PSD-bestand. Is ook een markup-interface die wordt gebruikt om zowel Verkochte als Enige bronnen aan te duiden in de Adobe® Photoshop®-afbeeldingen. |
## Opsomming

| Opsomming | Beschrijving |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Lagenvergrendelingsopties |
| [LayerSectionSubtype](./layersectionsubtype/) | Het sectiesubtype |
| [LayerSectionType](./layersectiontype/) | De laagsectie type |
| [LinkDataSourceType](./linkdatasourcetype/) | Definieert de LinkDataSourceType-opsomming voor de gegevensbronnen in de PSD-linkresource. |
| [LnsrResourceType](./lnsrresourcetype/) | Mogelijke Lnsr-brontypen ontdekt |
| [PlacedLayerType](./placedlayertype/) | Definieert de PlacedLayerType-opsomming voor de geplaatste laag PlLd-resource. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Mogelijke kleuren van bladkleurinstelling. Het is UI decoratieve kleur van laag in lagenlijst in PS |


