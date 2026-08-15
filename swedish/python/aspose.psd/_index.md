---
title: "aspose.psd"
type: docs
weight: 10
url: /sv/python-net/aspose.psd/
---


Modulen är kärnan för nästlade moduler och de mest grundläggande objekten som används för Aspose.PSD‑bearbetning.

## **Classes**
| **Klass** | **Beskrivning** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Definierar ett blandningsmönster. Denna klass kan inte ärvas. |
| [Brush](/psd/python-net/aspose.psd/brush/) | Baspenselklassen. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Innehåller den aktuella byggversionsinformationen. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Innehåller cacheinställningar. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | CMYK-färgen för pixeln. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Hjälpmetoder för att arbeta med CMYK-färg presenterad som ett signerat 32-bitars heltal.<br/>            Tillhandahåller ett liknande API som [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            Den är mer lättviktig eftersom CMYK-färg presenteras bara som Int32 snarare än en struktur med interna fält.<br/>            Använd gärna de statiska metoderna i denna klass när det är möjligt istället för den föråldrade<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct. |
| [Color](/psd/python-net/aspose.psd/color/) | Färgen på pixeln. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Definierar arrayer av färger och positioner som används för interpolering av färgblandning i ett flerfärgsgradient. Denna klass kan inte ärvas. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Definierar en karta för konvertering av färger. Flera metoder i klassen [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) justerar bildfärger genom att använda en färg‑omkartningstabell, som är en array av [ColorMap](/psd/python-net/aspose.psd/colormap/) strukturer. Inte ärvbar. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Definierar en 5 x 5-matris som innehåller koordinaterna för RGBA-rymden. Flera metoder i klassen [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) justerar bildfärger genom att använda en färgmatris. Denna klass kan inte ärvas. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Definierar en array av färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Inte ärvbar. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Hjälpklass för manipulation av färgpaletter. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Översätter färger till och från GDI+ Color-strukturer. Denna klass kan inte ärvas. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Inkapslar en anpassad användardefinierad linjekap. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | Behållaren för datastreamen. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Representerar ett disponibelt objekt. |
| [Figure](/psd/python-net/aspose.psd/figure/) | Figuren. En behållare för former. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Hjälpmedel för filströmshantering. |
| [Font](/psd/python-net/aspose.psd/font/) | Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut. Denna klass kan inte ärvas. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Allmänna PSD-vektormatrisrenderarens teckensnittsinställningar. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Representerar grafiken enligt den grafikmotor som används i den aktuella samlingen. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Representerar en serie av sammanhängande linjer och kurvor. Denna klass kan inte ärvas. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | Den avancerade buffertprocessorn. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | Buffertprocessorn. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | Färgkonverteraren. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | Färgpalettgränssnittet. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | Bildskaparen. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | Bildskapardeskriptorn som specificerar skaparegenskaperna. Skapardeskriptorn används för att övervinna<br/>            behovet av att hålla varje bildskaparinstans i minnet och problem med flertrådad körning. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | Bildbeskrivaren. Innehåller grundegenskaper och metoder för alla andra bildbeskrivartyper. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | Bildexportören. Kan exportera data från internt Aspose.PSD-format till ett specificerat dataformat. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Representerar bildexportörsdeskriptorn. Exportörsdeskriptorn används för att övervinna behovet av att hålla varje exportörinstans<br/>            i minnet och problem med flertrådad körning. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | Bildläsaren. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | Bildläsardeskriptorn som specificerar laddaregenskaperna. Laddardeskriptorn används för att övervinna<br/>            behovet av att hålla varje bildläsarinstans i minnet och problem med flertrådad körning. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | Färgkonverteraren för indexerade bildformat. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Representerar gränssnitt för objekt med nycklar. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Representerar ett objekt med gränser. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Representerar en ordnad form. En ordnad form är en kontinuerlig samling av punkter som har en startpunkt och en slutpunkt.<br/>            Den kontinuerliga samlingen av punkter som är sammankopplade med en specifik regel. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Uppfyller de 32-bitars ARGB-pixlarna som laddas delvis. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | Den 64-bitars ARGB-pixelsläsaren. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Uppfyller pixlarna som laddas delvis. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | Den partiella dataläsaren. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | Pasd-färgpaletten |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | Rasterbildens 32-bitars ARGB-pixelinläsare. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | Rasterbildens pixelinläsare. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | Rasterbildens rådatainläsare. |
| [Image](/psd/python-net/aspose.psd/image/) | Bilden är basklassen för alla typer av bilder. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Ett [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑objekt innehåller information om hur bitmap‑ och metafilfärger manipuleras under rendering. Ett [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑objekt upprätthåller flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalajusteringsmatriser, gamma‑korrektionsvärden, färgkartutabeller och färgtröskelvärden. Under rendering kan färger korrigeras, mörkras, ljusas upp och tas bort. För att tillämpa sådana manipulationer, initiera ett [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑objekt och skicka dess sökväg (tillsammans med sökvägen till en [Image](/psd/python-net/aspose.psd/image/)) till DrawImage‑metoden. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Representerar bildskaparnas register. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Representerar bildexportörernas register. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Representerar bildinläsarnas register. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | Bildens grundalternativ. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Klass för bildstorleksändringsinställningar. |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Klass för att representera en sekvens av element. |
| [License](/psd/python-net/aspose.psd/license/) | Tillhandahåller metoder för att licensiera komponenten. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Representerar inläsningsalternativen. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Ersätter GDI+‑matrisen. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Tillhandahåller metoder för att ställa in mätad nyckel. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Representerar en icke‑generisk ordbok. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Icke‑generisk lista med objekt. |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | Objektet med gränser. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Cache för OpenType‑typsnitt som är installerade i systemet. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Definierar ett objekt som används för att rita linjer, kurvor och figurer. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | Pixeldataformatet. Detta är ett oföränderligt objekt. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | Klassen för att lagra bildpixeldata och dess gränser. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Undantag för plugin‑licens. |
| [Point](/psd/python-net/aspose.psd/point/) | Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Representerar ett ordnat par av flyttals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Representerar en rasterbild som stöder rastergrafikoperationer. Denna bild cachar pixeldata vid behov. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Representerar en rasterbild som stöder rastergrafikoperationer. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | Inställningarna för rådata |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Lagrar en uppsättning av fyra heltal som representerar placeringen och storleken på en rektangel. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Lagrar en uppsättning av fyra flyttal som representerar placeringen och storleken på en rektangel. |
| [Region](/psd/python-net/aspose.psd/region/) | Beskriver insidan av en grafisk form bestående av rektanglar och banor. Denna klass kan inte ärvas. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | Upplösningsinställningen för bildsparalternativ. |
| [Shape](/psd/python-net/aspose.psd/shape/) | Formen. En kontinuerlig uppsättning punkter som är sammankopplade med en specifik regel. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Representerar ett formsegment. Ett segment är en linje eller kurva som förbinder två punkter. |
| [Size](/psd/python-net/aspose.psd/size/) | Representerar storlek. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Lagrar ett ordnat par av flyttal, vanligtvis bredden och höjden på en rektangel. |
| [Source](/psd/python-net/aspose.psd/source/) | Källan används för att innehålla all relevant information för ett objekt‑rör. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Representerar en delad strömbärare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Representerar en strömbärare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Inkapslar information om textlayout (såsom justering, orientering och tabbstopp), visningsmanipulationer (såsom ellipsis‑infogning och nationell siffrors ersättning) och OpenType‑funktioner. Denna klass kan inte ärvas. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | Objektet som stödjer transparens. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | Vektorbilden är basklassen för alla typer av vektorbilder. |
## **Enumerations**
| **Enumeration** | **Beskrivning** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Anger vilken cache‑typ som ska användas. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Representerar den använda teckenuppsättningen. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Anger vilka objekt som använder färgjusteringsinformation. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Anger enskilda kanaler i CMYK‑färgrymden (cyan, magenta, gul, svart). Denna uppräkning används av metoderna SetOutputChannel. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Färgjämförelsesmetod för att justera till närmaste granne |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Anger vilka typer av bilder och färger som kommer att påverkas av färg- och gråskalajusteringsinställningarna för ett [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Metoder för färgkvantisering |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Anger vilken kvalitetsnivå som ska användas vid sammansättning. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Anger vilken typ av grafisk form som ska användas i båda ändarna på varje streck i en streckad linje. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Anger stilen för streckade linjer som ritas med ett [Pen](/psd/python-net/aspose.psd/pen/)‑objekt. |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | Datåterställningsläget. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Dithermetod. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | Dithermetoderna som används för att kontrollera färgkonvertering. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | Ett av de stödjade PSD‑filformaten. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Anger hur insidan av en sluten bana fylls. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Anger stilinformation som tillämpas på text. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Anger måttenheten för de givna data. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Anger de olika mönstren som är tillgängliga för [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/)‑objekt. |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Anger vilken typ av visning som används för snabbtangentsprefix som relaterar till text. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Bildfilter att använda |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | Enumen [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) anger algoritmen som används när bilder skalas eller roteras. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Anger de kända systemfärgerna. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Anger de tillgängliga spetsstilarna som ett [Pen](/psd/python-net/aspose.psd/pen/)‑objekt kan avsluta en linje med. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Anger hur man förenar på varandra följande linje- eller kurvsegment i en figur (underbana) som finns i ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt. |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Anger ordningen för matrisomvandlingsoperationer. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Anger PDF‑kompatibilitetsnivån för utdatafilen. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Anger justeringen av ett [Pen](/psd/python-net/aspose.psd/pen/)‑objekt i förhållande till den teoretiska linjen med noll bredd. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Anger vilken typ av fyllning ett [Pen](/psd/python-net/aspose.psd/pen/)‑objekt använder för att fylla linjer. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | Den faktiska betydelsen av pixeldataformatet. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Anger typ av storleksändring. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Upplösningsenhets‑enum. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Anger hur mycket en bild roteras och vilken axel som används för att vända bilden. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Tillhandahåller fälten som representerar referenspunkter i [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) för sökning. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Anger om jämning (antialiasing) tillämpas på linjer och kurvor samt kanterna på fyllda områden. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Anger justeringen av en textsträng i förhållande till dess layoutrektangel. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | Uppräkningen specificerar hur siffror i en sträng ska ersättas enligt en användares språk eller lokala inställning. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Anger visnings- och layoutinformation för textsträngar. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Anger hur tecken ska trimmas från en sträng som inte helt får plats i en layoutform. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Anger kvaliteten på textåtergivning. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Anger typen av warp‑transformation som tillämpas. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Anger hur en textur eller gradient tileas när den är mindre än det område som fylls. |
