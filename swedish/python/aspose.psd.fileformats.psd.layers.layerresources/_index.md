---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **Klass** | **Beskrivning** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | Artboard-informationsdata. |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | Bas-klass för justeringslagerresurser |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | Sektion med animerade data. |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | Artboard-informationsdata för [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | Artboard-informationsdata för [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | Artboard-informationsdataresurs. |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | BlncResource-klass är en resurs för färgjusteringslager. |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | BlwhResource-klass är en resurs för svartvitt justeringslager. |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | Klassen BooleanResource. Det är en pseudo-resurs. Photoshop har den inte. |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | Klassen BritResource. Resurs för ljusstyrka/kontrast-justeringslager |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | Klassen CgEdResource. Innehållsgenerator extra data (Photoshop CS5) |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | PSD-klass-ID-objektet. |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | Klass ClblResource.<br/>            Denna resurs innehåller information om blandning av beskuret element. |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | Klass CmlsResource. |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) har 6 färgområden där du kan ändra HSV-parametrar. <br/>            Varje område har 4 nyckelpunkter för att identifiera områdesgränser. Och det är ColorRangeHsl |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | Klass CurvResource. Resurs för Curves Adjustment Layer<br/>            1 byte - 0 om kurvor används, 1 om pixlar på karta används<br/>            om 0 då:<br/>            2 bytes - short. Standard är 1<br/>            4 bytes - int. Används endast sista byte per bit. Första biten är för 1 kanal, den fjärde biten för 4 kanaler som exempel<br/>            2 bytes - short antal punkter<br/>            4 bytes * antal punkter - kurvpunkter 2 short: första positionen, andra höjden<br/>            4 bytes - ordet \"Crv \"<br/>            2 bytes - short standard är 4 för Curves<br/>            4 bytes - int. Standard är 1<br/>            4 bytes - antal punkter<br/>            4 bytes * antal punkter - kurvpunkter 2 short: första positionen, andra höjden<br/>            0-4 bytes - Ledande för att vikas för fyra<br/>            om 1 då:<br/>            2 bytes - short. Standard är 1<br/>            4 bytes - int. Används endast sista byte. En kanal är i en bit. Första biten är för 1 kanal, den fjärde biten för 4 kanaler som exempel<br/>            256 * antal ändrade kanaler - ordnade värden för kanal i intervallet 0 - 255<br/>            4 bytes - ordet \"Crv \"<br/>            2 bytes - short. Standard är 3 för pixlar på karta<br/>            4 bytes - int Kanalantal<br/>            (2 + 256) bytes - short 2 för kanalindex, 256 är ordnade värden för kanal i intervallet 0 - 255 |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | Manager för Curves Adjustment Layer som manipulerar kurvor |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | Manager för Curves Adjustment Layer som manipulerar pixelkartan |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | Basklass för att hantera CurvResource |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | Klass CustResource.<br/>            Denna resurs innehåller information om blandning av beskuret element. |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | Klass ExpaResource. Resurs för Exposure Adjustment Layer |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | Filter Effects-resursen innehåller kanaler, en användarmask och ett bladmask för det smarta filtret. |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | Basklass för fyllnadslagerresurser. |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | Filtermaskens dataklass. |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | Klass FxrpResource. Lagrets referenspunkt |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | Klass GdFlResource.<br/>            Denna resurs innehåller information om blandning av beskuret element. |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | Klass GrdmResource. Innehåller information om Gradient-Map-lager. |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | Klass Hue2Resource. Resurs för Exposure Adjustment Layer |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | Den [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resursladdaren. |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | Gränssnittet beskriver mängden Paths som finns i ett Shape-lager. |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | Shape från knutarna i Bezier-kurvan. |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | Definierar IPlacedLayerResource-gränssnittet som innehåller information om ett placerat lager i PSD-filen.<br/>            Det är ett markup‑gränssnitt som används för att ange PlLd-, Sold- och Sole‑resurser i Adobe® Photoshop®‑bilder.<br/>            Det används för att stödja smarta objekt‑lager i Adobe® Photoshop®‑bilder. |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | Definierar ISmartObjectLayerResource‑gränssnittet som innehåller information om en smart objekt‑lagerresurs i PSD‑filen.<br/>            Det är också ett markup‑gränssnitt som används för att beteckna både Sold‑ och Sole‑resurser i Adobe® Photoshop®‑bilder. |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | Klass InfxResource.<br/>            Denna resurs innehåller information om blandning av klippt element. |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | Klass IopaResource.<br/>            Denna resurs innehåller information om fyllningsopacitetsegenskapen från lagerstilsformuläret |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | Klass KnkoResource.<br/>            Denna resurs innehåller information om blandning av klippt element. |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | Lagersektionens resurs. |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | Klass LclrResource.<br/>            Denna resurs innehåller information om lagerfärg i lagerlistan i PS. Det är endast |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | Klass för att arbeta med kanaler i Nivåjusteringslager |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | Klass LevlResource. Resurs för Exponeringsjusteringslager |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Lfx2‑resurs (effektresurs) |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | Definierar liFD‑datakällklassen i PSD‑filen som innehåller information om en inbäddad fil.<br/>            Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop®‑filer |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | Definierar LnkeDataSource‑klassen som innehåller information om en extern länkad fil.<br/>            Detta är en del av PSD File Format Manipulation API som hjälper till att modifiera Adobe® Photoshop®‑filer |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | Definierar LinkDataSource‑klassen som innehåller information om en länkad fil eller en tillgång i PSD‑filen. |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | Definierar LinkResource‑klassen som innehåller information om länkade eller inbäddade filer i PSD‑formatets bild.<br/>            Länkresursen kan innehålla flera [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)‑instanser som kan nås via indexerare i alla avledda klasser. |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | LMsk‑resursen. |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | Definierar klassen som innehåller information om inbäddade filer i PSD‑formatets bild.<br/>            Länkresursen kan innehålla flera [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/)‑instanser som kan nås via indexeraren. |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | Definierar klassen som innehåller information om en inbäddad fil i PSD‑formatets 32‑bit per kanal‑bild.<br/>            Länkresursen kan innehålla flera [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/)‑instanser som kan nås via indexeraren. |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | Definierar LnkeResource‑klassen som innehåller information om externa länkade filer eller tillgångar i PSD‑formatets bild.<br/>            Länkresursen kan innehålla flera [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/)‑instanser som kan nås via indexeraren.<br/>            Detta är en del av PSD File Format Manipulation API som hjälper till att programatiskt modifiera Adobe® Photoshop®‑filer. |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | Klass lnsrResource. |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | lr16‑resursen. |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | lr32‑resursen. |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | lrXX‑resursen. |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | Lagrets skyddade inställningar |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | Lagernamnsresurs |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | Klass LyidResource. |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | Resursen som representerar Photoshop‑versionen av lagret. |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | Klass MixrResource. Resurs för Kanalblandare justeringslager |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | mlst-resursen.<br/>            Denna klass, bland annat, innehåller information om lagrets position på tidslinjen. |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | Klass NvrtResource. Resurs för Invertera justeringslager. |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | Representerar OS-typstrukturen. |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | Representerar [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resursernas register. |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | Figuren från knutarna i Bézier-kurvan. |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | Klass PattResource. Resurs med mönsterdata |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | Klassen för att lagra mönsterdata för [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resursen. |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | Klass PhflResource. Resurs för Exponering justeringslager<br/>            2 Version ( = 3 ) eller ( = 2 )<br/>            12 4 byte vardera för XYZ-färg (Endast i Version 3)<br/>            10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (Endast i Version 2)<br/>            4 Densitet<br/>            1 Bevara luminans |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | Klass PhflResource. Resurs för Exponering justeringslager<br/>            2 Version ( = 3 ) eller ( = 2 )<br/>            12 4 byte vardera för XYZ-färg (Endast i Version 3)<br/>            10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (Endast i Version 2)<br/>            4 Densitet<br/>            1 Bevara luminans |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | Klass PhflResource. Resurs för Exponering justeringslager<br/>            2 Version ( = 3 ) eller ( = 2 )<br/>            12 4 byte vardera för XYZ-färg (Endast i Version 3)<br/>            10 2 byte färgrymd följt av 4 * 2 byte färgkomponent (Endast i Version 2)<br/>            4 Densitet<br/>            1 Bevara luminans |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | Definierar klassen PlLdResource som innehåller information om ett placerat lager i PSD-filen.<br/>            Används för att stödja smarta objektlager i Adobe‑Photoshop‑bilder.<br/>            Den ersattes av SoLdResource i Adobe‑Photoshop‑CS3 |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | Definierar klassen PlacedResource som innehåller gemensam information om ett placerat lager eller ett smart objektlager i PSD-filen.<br/>            Används för att stödja smarta objektlager i Adobe‑Photoshop‑bilder. |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | Klass PostResource. Posteriseringslagerinställningar. |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | Klass PtFlResource. Innehåller data för mönsterfyllningslager. |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | Klass ShmdResource. Metadata‑inställningar |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | Definierar klassen SmartObjectResource som innehåller information om ett smart objektlager i en PSD‑fil.<br/>            Är basklassen för Sold‑ och Sole‑resurser som används för att stödja smarta objektlager i Adobe‑Photoshop‑bilder. |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | Definierar klassen SmartResourceCreator som kan skapa PlLd‑, SoLd‑ och SoLe‑resurser.<br/>            Används för att stödja smarta objektlager i Adobe® Photoshop®‑bilder. |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | Klass SoCoResource.<br/>            Denna resurs innehåller information om färgfyllningslager |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | Definierar klassen SoLdResource som innehåller information om ett smart objektlager i en PSD‑fil.<br/>            Används för att stödja smarta objektlager i Adobe‑Photoshop‑bilder. |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | Definierar klassen SoLeResource som innehåller information om ett smart objektlager i en PSD‑fil.<br/>            Används för att stödja smarta objektlager med externa fillänkar i Adobe‑Photoshop‑bilder. |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Txt2‑resursklass |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | Innehåller information om typsnitt för textverktyget. |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | Information om textverktyget. För PSD‑version högre än eller lika med 6.0. |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | Information om textverktyget. För PSD‑version lägre än 6.0. |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | Radinformation för textverktyget. |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | Stilinformation för textverktyget. |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | Den okända resursen. |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | Klassen som innehåller vektorvägar. |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | Klass VectorPathDataResource.<br/>            Denna resurs innehåller information om vektorlagermask. |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | VibA-resurs. |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | Klass VmskResource.<br/>            Denna resurs innehåller information om vektorlagermask. |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | Den vektorursprungsdataresursen. |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | Klass VsmsResource.<br/>            Denna resurs innehåller information om vektorlagermask. |
## **Enumerations**
| **Enumeration** | **Beskrivning** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | Låsningsalternativ för lager |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | Avsnittets undertyp |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | Lagrets avsnittstyp |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | Definierar uppräkningen LinkDataSourceType för datakällorna i PSD-länkreursen. |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | Upptäckta möjliga Lnsr-resurstyper |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | Definierar uppräkningen PlacedLayerType för den placerade lagern PlLd-resursen. |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | Möjliga färger för bladfärgsinställning.<br/>            Det är ett UI-dekorativt färg för lager i lagerlistan i PS. |
