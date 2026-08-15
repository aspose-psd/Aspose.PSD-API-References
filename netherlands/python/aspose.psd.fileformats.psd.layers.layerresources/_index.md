---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **Klasse** | **Beschrijving** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | De Artboard-informatiedata. |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | Basisklasse voor aanpassingslaagbronnen |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | De sectie met geanimeerde gegevens. |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | De Artboard-informatiedata voor [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | De Artboard-informatiedata voor [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | De Artboard-informatiedataresource. |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | BlncResource-klasse is een bron van Kleuraanpassingslaag. |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | BlwhResource-klasse is een bron van Zwart-wit-aanpassingslaag. |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | Klasse BooleanResource. Het is een pseudo-bron. Photoshop heeft deze niet |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | Klasse BritResource. Bron van Helderheid/Contrast-aanpassingslaag |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | Klasse CgEdResource. Content Generator Extra Data (Photoshop CS5) |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | Het PSD Class ID-object. |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | Klasse ClblResource.<br/>            Deze bron bevat informatie over het mengen van een geknipte element. |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | Klasse CmlsResource. |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) heeft 6 kleurbereiken waarin je HSV-parameters kunt wijzigen. <br/>            Elk bereik heeft 4 sleutelpunten om de grenzen van het bereik te identificeren. En het is ColorRangeHsl |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | Klasse CurvResource. Bron van Curves-aanpassingslaag<br/>            1 byte - 0 als curven worden gebruikt, 1 als pixels op de kaart worden gebruikt<br/>            als 0 dan:<br/>            2 bytes - short. Standaard is 1<br/>            4 bytes - int. Alleen het laatste byte wordt per bit gebruikt. Het eerste bit is voor 1 kanaal, het vierde bit voor 4 kanalen bijvoorbeeld<br/>            2 bytes - short puntentelling<br/>            4 bytes * aantal punten - punten van de curve 2 short: eerste positie, tweede hoogte<br/>            4 bytes - woord "Crv "<br/>            2 bytes - short, standaard is 4 voor Curves<br/>            4 bytes - int. Standaard is 1<br/>            4 bytes - puntentelling<br/>            4 bytes * puntentelling - punten van de curve 2 short: eerste positie, tweede hoogte<br/>            0-4 bytes - Leidend om te vouwen voor vier<br/>            als 1 dan:<br/>            2 bytes - short. Standaard is 1<br/>            4 bytes - int. Alleen het laatste byte wordt gebruikt. Eén kanaal is één bit. Het eerste bit is voor 1 kanaal, het vierde bit voor 4 kanalen bijvoorbeeld<br/>            256 * aantal gewijzigde kanalen - geordende waarden van het kanaal in bereik 0 - 255<br/>            4 bytes - woord "Crv "<br/>            2 bytes - short. Standaard is 3 voor pixels op de kaart<br/>            4 bytes - int Kanaaltelling<br/>            (2 + 256) bytes - short 2 voor kanaalindex, 256 is geordende waarden van het kanaal in bereik 0 - 255 |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | Beheerder voor Curves-aanpassingslaag die curven manipuleert |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | Beheerder voor Curves Adjustment Layer die de pixelkaart bewerkt |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | Basisklasse om CurvResource te beheren |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | Class CustResource.<br/>            Deze resource bevat informatie over het mengen van een geknipte element. |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | Class ExpaResource. Resource van Exposure Adjustment Layer |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | De Filter Effects resource bevat kanalen, een gebruikersmasker en een sheetmasker voor de slimme filter. |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | Basisklasse voor vullaagresources. |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | De filtermaskergegevensklasse. |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | Class FxrpResource. Het referentiepunt van de laag |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | Class GdFlResource.<br/>            Deze resource bevat informatie over het mengen van een geknipte element. |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | Class GrdmResource. Bevat informatie over Gradient-Map laag. |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | Class Hue2Resource. Resource van Exposure Adjustment Layer |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | De [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resourceloader. |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | Interface beschrijft de set van Paths die aanwezig zijn in een Shape-laag. |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | De Shape van de knopen van de Bezier-curve. |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | Definieert de IPlacedLayerResource interface die informatie bevat over een geplaatste laag in het PSD‑bestand.<br/>            Het is een markup‑interface die wordt gebruikt om PlLd-, Sold- en Sole‑resources aan te duiden in de Adobe® Photoshop®‑afbeeldingen.<br/>            Het wordt gebruikt om smart object‑lagen te ondersteunen in de Adobe® Photoshop®‑afbeeldingen. |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | Definieert de ISmartObjectLayerResource interface die informatie bevat over een smart object‑layerresource in het PSD‑bestand.<br/>            Het is ook een markup‑interface die wordt gebruikt om zowel Sold- als Sole‑resources aan te duiden in de Adobe® Photoshop®‑afbeeldingen. |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | Class InfxResource.<br/>            Deze resource bevat informatie over het mengen van een geknipte element. |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | Class IopaResource.<br/>            Deze resource bevat informatie over de vul‑opaciteit‑eigenschap van het laag‑stijlvormulier |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | Class KnkoResource.<br/>            Deze resource bevat informatie over het mengen van een geknipte element. |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | De laagsectie‑resource. |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | Class LclrResource.<br/>            Deze resource bevat informatie over de kleur van de laag in de lagenlijst van PS. Het is alleen |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | Class voor het werken met kanalen in Levels Adjustment Layer |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | Class LevlResource. Resource van Exposure Adjustment Layer |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Lfx2 resource (effectenresource) |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | Definieert de liFD‑datasource‑klasse in PSD‑bestand die informatie bevat over een ingebed bestand.<br/>            Dit is onderdeel van de PSD File Format Manipulation API die helpt bij het aanpassen van Adobe® Photoshop®‑bestanden |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | Definieert de LnkeDataSource-klasse die informatie bevat over een extern gekoppeld bestand.<br/>            Dit is onderdeel van de PSD File Format Manipulation API die helpt bij het wijzigen van Adobe® Photoshop®-bestanden |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | Definieert de LinkDataSource-klasse die informatie bevat over een gekoppeld bestand of een asset in het PSD‑bestand. |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | Definieert de LinkResource-klasse die informatie bevat over gekoppelde of ingesloten bestanden in de PSD‑formaatafbeelding.<br/>            De linkresource kan verschillende [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)‑instanties bevatten die via indexers in elke afgeleide klasse toegankelijk zijn. |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | De LMsk‑resource. |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | Definieert de klasse die informatie bevat over ingesloten bestanden in de PSD‑formaatafbeelding.<br/>            De linkresource kan verschillende [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/)‑instanties bevatten die via de indexer toegankelijk zijn. |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | Definieert de klasse die informatie bevat over een ingesloten bestand in de PSD‑formaatafbeelding met 32 bit per kanaal.<br/>            De linkresource kan verschillende [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/)‑instanties bevatten die via de indexer toegankelijk zijn. |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | Definieert de LnkeResource-klasse die informatie bevat over externe gekoppelde bestanden of assets in de PSD‑formaatafbeelding.<br/>            De linkresource kan verschillende [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)‑instanties bevatten die via de indexer toegankelijk zijn.<br/>            Dit is een onderdeel van de PSD File Format Manipulation API die helpt Adobe® Photoshop®-bestanden programmatisch te wijzigen. |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | Klasse lnsrResource. |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | De lr16‑resource. |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | De lr32‑resource. |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | De lrXX‑resource. |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | Beschermde laaginstellingen |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | Laagnaam‑resource |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | Klasse LyidResource. |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | De resource die de Photoshop‑versie van de laag weergeeft. |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | Klasse MixrResource. Resource van Channel Mixer Adjustment Layer |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | De mlst‑resource.<br/>            Deze klasse bevat onder andere informatie over de positie van de laag op de tijdlijn. |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | Klasse NvrtResource. Resource van Invert Adjustment Layer. |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | Stelt de OS‑type‑structuur voor. |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | Stelt het [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources‑register voor. |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | De figuur van de knopen van de Bézier‑curve. |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | Klasse PattResource. Resource met patroon‑gegevens |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | De klasse om de patroon‑gegevens op te slaan voor de [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/)‑resource. |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | Klasse PhflResource. Resource van Exposure Adjustment Layer<br/>            2 Versie ( = 3 ) of ( = 2 )<br/>            12 4 bytes per XYZ‑kleur (alleen in Versie 3)<br/>            10 2 bytes kleurruimte gevolgd door 4 × 2 bytes kleurcomponent (alleen in Versie 2)<br/>            4 Dichtheid<br/>            1 Luminantie behouden |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | Klasse PhflResource. Resource van Exposure Adjustment Layer<br/>            2 Versie ( = 3 ) of ( = 2 )<br/>            12 4 bytes per XYZ‑kleur (alleen in Versie 3)<br/>            10 2 bytes kleurruimte gevolgd door 4 × 2 bytes kleurcomponent (alleen in Versie 2)<br/>            4 Dichtheid<br/>            1 Luminantie behouden |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | Klasse PhflResource. Resource van Exposure Adjustment Layer<br/>            2 Versie ( = 3 ) of ( = 2 )<br/>            12 4 bytes per XYZ‑kleur (alleen in Versie 3)<br/>            10 2 bytes kleurruimte gevolgd door 4 × 2 bytes kleurcomponent (alleen in Versie 2)<br/>            4 Dichtheid<br/>            1 Luminantie behouden |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | Definieert de PlLdResource-klasse die informatie bevat over een geplaatste laag in het PSD‑bestand.<br/>            Wordt gebruikt om smart‑object‑lagen in Adobe® Photoshop®‑afbeeldingen te ondersteunen.<br/>            Het werd vervangen door SoLdResource in Adobe® Photoshop® CS3 |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | Definieert de PlacedResource-klasse die algemene informatie bevat over een geplaatste laag of een smart object-laag in het PSD‑bestand.<br/>            Wordt gebruikt om smart object-lagen te ondersteunen in de Adobe Photoshop‑afbeeldingen. |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | Klasse PostResource. Posterize-laaginstellingen. |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | Klasse PtFlResource. Bevat gegevens van patroonvullingslaag. |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | Klasse ShmdResource. Metagegevensinstellingen |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | Definieert de SmartObjectResource-klasse die informatie bevat over een smart object-laag in een PSD‑bestand.<br/>            Is de basisklasse voor Sold‑ en Sole‑resources die wordt gebruikt om smart object-lagen te ondersteunen in de Adobe Photoshop‑afbeeldingen. |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | Definieert de SmartResourceCreator‑klasse die PlLd-, SoLd- en SoLe‑resources kan aanmaken.<br/>            Wordt gebruikt om smart object-lagen te ondersteunen in de Adobe® Photoshop®‑afbeeldingen. |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | Klasse SoCoResource.<br/>            Deze resource bevat informatie over kleurvullingslagen |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | Definieert de SoLdResource‑klasse die informatie bevat over een smart object‑laag in een PSD‑bestand.<br/>            Wordt gebruikt om smart object‑lagen te ondersteunen in de Adobe Photoshop‑afbeeldingen. |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | Definieert de SoLeResource‑klasse die informatie bevat over een smart object‑laag in een PSD‑bestand.<br/>            Wordt gebruikt om smart object‑lagen met externe bestandskoppelingen te ondersteunen in de Adobe Photoshop‑afbeeldingen. |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Txt2‑resourceklasse |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | Bevat informatie over het lettertype van het typegereedschap. |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | De typegereedschap‑informatie. Voor PSD‑versies hoger of gelijk aan 6.0. |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | De typegereedschap‑informatie. Voor PSD‑versies lager dan 6.0. |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | Regelinfo van het typegereedschap. |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | Stijlinformatie van het typegereedschap. |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | De onbekende resource. |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | De klasse die vectorpaden bevat. |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | Klasse VectorPathDataResource.<br/>            Deze resource bevat informatie over een vector‑lagenmasker |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | VibA‑resource. |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | Klasse VmskResource.<br/>            Deze resource bevat informatie over een vector‑lagenmasker |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | De Vector‑origination‑dataresource. |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | Klasse VsmsResource.<br/>            Deze resource bevat informatie over een vector‑lagenmasker |
## **Enumerations**
| **Enumeratie** | **Beschrijving** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | Opties voor laagvergrendeling |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | Het sectiesubtype |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | Het type laagsectie |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | Definieert de enumeratie LinkDataSourceType voor de gegevensbronnen in de PSD‑koppelingsresource. |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | Ontdekte mogelijke Lnsr resource types. |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | Definieert de enumeratie PlacedLayerType voor de geplaatste laag PlLd resource. |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | Mogelijke kleuren van de Sheet‑kleurinstelling.<br/>            Het is een UI‑decoratieve kleur van de laag in de lagenlijst in PS |
