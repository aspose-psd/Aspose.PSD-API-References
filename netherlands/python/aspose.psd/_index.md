---
title: "aspose.psd"
type: docs
weight: 10
url: /nl/python-net/aspose.psd/
---


De module is de kern voor geneste modules en de meest basale objecten die worden gebruikt voor Aspose.PSD-verwerking.

## **Classes**
| **Klasse** | **Beschrijving** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Definieert een mengpatroon. Deze klasse kan niet worden geërfd. |
| [Brush](/psd/python-net/aspose.psd/brush/) | De basis penseelklasse. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Bevat de huidige buildversie-informatie. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Bevat cache-instellingen. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | De CMYK-kleur van de pixel. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Helpermethoden om te werken met CMYK-kleur gepresenteerd als een ondertekend 32-bit geheel getal.<br/>            Biedt een vergelijkbare API als de [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            Het is lichter omdat CMYK-kleur alleen als Int32 wordt gepresenteerd in plaats van als een structuur met interne velden.<br/>            Gebruik bij voorkeur de statische methoden van deze klasse wanneer mogelijk in plaats van de verouderde<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct. |
| [Color](/psd/python-net/aspose.psd/color/) | De kleur van de pixel. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Definieert arrays van kleuren en posities die worden gebruikt voor het interpoleren van kleurvervaging in een meerkleurige gradient. Deze klasse kan niet worden geërfd. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Definieert een kaart voor het converteren van kleuren. Verschillende methoden van de [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) klasse passen afbeeldingskleuren aan door gebruik te maken van een kleur-herkaarttabel, die een array van [ColorMap](/psd/python-net/aspose.psd/colormap/) structuren is. Niet erftbaar. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Definieert een 5 x 5 matrix die de coördinaten voor de RGBA-ruimte bevat. Verschillende methoden van de [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) klasse passen afbeeldingskleuren aan door gebruik te maken van een kleurmatrix. Deze klasse kan niet worden geërfd. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Definieert een array van kleuren die een kleurenpalet vormen. De kleuren zijn 32-bit ARGB-kleuren. Niet erftbaar. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Helperklasse voor manipulatie van kleurenpaletten. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Vertaal kleuren naar en van GDI+ Color-structuren. Deze klasse kan niet worden geërfd. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Omvat een aangepaste door de gebruiker gedefinieerde lijnkap. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | De gegevensstroomcontainer. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Stelt een wegwerpbaar object voor. |
| [Figure](/psd/python-net/aspose.psd/figure/) | De figuur. Een container voor vormen. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Helper voor bestandsstroomverwerking. |
| [Font](/psd/python-net/aspose.psd/font/) | Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken. Deze klasse kan niet worden geërfd. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Algemene PSD-vectorformaten renderer lettertype-instellingen. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Stelt de graphics voor volgens de graphicsengine die in de huidige assembly wordt gebruikt. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Stelt een reeks verbonden lijnen en krommen voor. Deze klasse kan niet worden geërfd. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | De geavanceerde bufferprocessor. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | De bufferprocessor. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | De kleurconverter. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | De kleurenpaletinterface. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | De afbeeldingmaker. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | De afbeeldingsmakerdescriptor die de maker‑eigenschappen specificeert. De makerdescriptor wordt gebruikt om<br/>            de noodzaak te omzeilen om elke afbeeldingsmakerinstantie in het geheugen te behouden en problemen met multithreading. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | De afbeeldingsdescriptor. Bevat basiseigenschappen en -methoden voor alle andere afbeeldingsdescriptor‑types. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | De afbeeldingsexporteur. Kan gegevens exporteren van het interne Aspose.PSD‑formaat naar een gespecificeerd gegevensformaat. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Stelt de afbeeldingsexporteurdescriptor voor. De exporteurdescriptor wordt gebruikt om de noodzaak te omzeilen om elke exporteurinstantie<br/>            in het geheugen te behouden en problemen met multithreading. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | De afbeeldingslader. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | De afbeeldingsladerdescriptor die de lader‑eigenschappen specificeert. De laderdescriptor wordt gebruikt om<br/>            de noodzaak te omzeilen om elke afbeeldingsladerinstantie in het geheugen te behouden en problemen met multithreading. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | De kleurconverter voor geïndexeerde afbeeldingsformaten. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Stelt de interface voor objecten met sleutels voor. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Stelt een object met grenzen voor. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Stelt een geordende vorm voor. Een geordende vorm is een doorlopende reeks punten met een startpunt en eindpunt.<br/>            De doorlopende reeks punten die met een specifieke regel is verbonden. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Voldoet aan de gedeeltelijk geladen 32‑bit ARGB‑pixels. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | De 64‑bit ARGB‑pixelloader. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Voldoet aan de gedeeltelijk geladen pixels. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | De gedeeltelijke gegevenslader. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | Het pasd‑kleurenpalet |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | De rasterafbeelding 32‑bit ARGB‑pixelloader. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | De rasterafbeelding pixelloader. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | De rasterafbeelding ruwe gegevenslader. |
| [Image](/psd/python-net/aspose.psd/image/) | De afbeelding is de basisklasse voor alle soorten afbeeldingen. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object bevat informatie over hoe bitmap‑ en metafilekleuren worden gemanipuleerd tijdens het renderen. Een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object onderhoudt verschillende kleurcorrectie‑instellingen, inclusief kleurcorrectiematrices, grijstinten‑correctiematrices, gamma‑correctiewaarden, kleurkaarttabellen en kleur‑drempelwaarden. Tijdens het renderen kunnen kleuren worden gecorrigeerd, verduisterd, opgehelderd en verwijderd. Om dergelijke manipulaties toe te passen, initialiseert u een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object en geeft u het pad van dat [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (samen met het pad van een [Image](/psd/python-net/aspose.psd/image/)) door aan de DrawImage‑methode. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Stelt het register van afbeeldingsmakers voor. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Stelt het register van afbeeldingsexporteurs voor. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Stelt het register van afbeeldingsladers voor. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | De afbeeldingsbasisopties. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Afbeeldingsgrootte‑aanpassingsinstellingen klasse |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Klasse voor het vertegenwoordigen van een reeks elementen |
| [License](/psd/python-net/aspose.psd/license/) | Biedt methoden om het component te licenseren. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Stelt de laadopties voor. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Vervangt de GDI+ Matrix. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Biedt methoden om een meter-sleutel in te stellen. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Stelt een niet-generiek woordenboek voor. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Niet-generieke lijst van objecten |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | Het object met grenzen. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Cache voor OpenType-lettertypen die in het systeem zijn geïnstalleerd. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Definieert een object dat wordt gebruikt om lijnen, krommen en figuren te tekenen. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | Het pixelgegevensformaat. Dit is een onveranderlijk object. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | De klasse om afbeeldingspixelgegevens en de grenzen ervan op te slaan. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Uitzondering voor plug-inlicentie |
| [Point](/psd/python-net/aspose.psd/point/) | Stelt een geordend paar van gehele x- en y-coördinaten voor dat een punt in een tweedimensionaal vlak definieert. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Stelt een geordend paar van zwevende-komma x- en y-coördinaten voor dat een punt in een tweedimensionaal vlak definieert. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Stelt een rasterafbeelding voor die rastergrafische bewerkingen ondersteunt. Deze afbeelding cachet pixelgegevens wanneer nodig. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Stelt een rasterafbeelding voor die rastergrafische bewerkingen ondersteunt. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | De ruwe gegevensinstellingen |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek vertegenwoordigen. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Slaat een set van vier zwevende-komma getallen op die de locatie en grootte van een rechthoek vertegenwoordigen. |
| [Region](/psd/python-net/aspose.psd/region/) | Beschrijft het interieur van een grafische vorm bestaande uit rechthoeken en paden. Deze klasse kan niet worden geërfd. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | De resolutie-instelling voor afbeeldingsopslagopties. |
| [Shape](/psd/python-net/aspose.psd/shape/) | De vorm. Een doorlopende set punten verbonden met een specifieke regel. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Stelt een vormsegment voor. Een segment is een lijn of kromme die twee punten verbindt. |
| [Size](/psd/python-net/aspose.psd/size/) | Stelt grootte voor. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Slaat een geordend paar zwevende-kommagetallen op, meestal de breedte en hoogte van een rechthoek. |
| [Source](/psd/python-net/aspose.psd/source/) | De bron wordt gebruikt om alle relevante informatie voor een objectpijp te bevatten. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Stelt een gesplitste streamcontainer voor die de stream bevat en streamverwerkingsroutines biedt. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Stelt een streamcontainer voor die de stream bevat en streamverwerkingsroutines biedt. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Omvat tekstindelingsinformatie (zoals uitlijning, oriëntatie en tabstops) weergavebewerkingen (zoals invoegen van ellipsis en nationale cijfervervanging) en OpenType-functies. Deze klasse kan niet worden geërfd. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | Het object dat transparantie ondersteunt. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | De vectorafbeelding is de basisklasse voor alle soorten vectorafbeeldingen. |
## **Enumerations**
| **Enumeratie** | **Beschrijving** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Specificeert het te gebruiken cachetype. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Stelt de gebruikte tekenset voor. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Specificeert welke objecten kleuraanpassingsinformatie gebruiken. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Specificeert individuele kanalen in de CMYK (cyaan, magenta, geel, zwart) kleurenruimte. Deze enumeratie wordt gebruikt door de SetOutputChannel-methoden. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Kleurvergelijkingsmethode om aan te passen aan de dichtstbijzijnde buur. |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Specificeert de typen afbeeldingen en kleuren die worden beïnvloed door de kleur- en grijstintaanpassingsinstellingen van een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Kleurenkwantisatiemethoden |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Specificeert het kwaliteitsniveau dat tijdens compositing moet worden gebruikt. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Specificeert het type grafische vorm dat aan beide uiteinden van elke streep in een gestippelde lijn moet worden gebruikt. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Specificeert de stijl van gestippelde lijnen die met een [Pen](/psd/python-net/aspose.psd/pen/) object worden getekend. |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | De gegevensherstelmodus. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Ditheringsmethode. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | De ditheringsmethoden die worden gebruikt om kleurconversie te beheersen. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | Een van de ondersteunde PSD-bestandsformaten. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Specificeert hoe het binnenste van een gesloten pad wordt gevuld. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Specificeert stijlinformatie die op tekst wordt toegepast. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Specificeert de meeteenheid voor de gegeven gegevens. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Specificeert de verschillende patronen die beschikbaar zijn voor [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/) objecten. |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Specificeert het type weergave voor sneltoetsvoorvoegsels die betrekking hebben op tekst. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Te gebruiken afbeeldingsfilters |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | De [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) enumeratie specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Specificeert de bekende systeemkleuren. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Specificeert de beschikbare cap-stijlen waarmee een [Pen](/psd/python-net/aspose.psd/pen/) object een lijn kan beëindigen. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Specificeert hoe opeenvolgende lijn- of krommesegmenten in een figuur (subpad) die zich bevindt in een [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) object worden samengevoegd. |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Specificeert de volgorde voor matrixtransformatie‑operaties. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Specificeert het PDF‑conformiteitsniveau voor het uitvoerbestand. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Specificeert de uitlijning van een [Pen](/psd/python-net/aspose.psd/pen/) object ten opzichte van de theoretische, nul‑breedte lijn. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Specificeert het type vulling dat een [Pen](/psd/python-net/aspose.psd/pen/) object gebruikt om lijnen te vullen. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | De daadwerkelijke betekenis van het pixelgegevensformaat. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Specificeert het type herschaling. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Resolutie‑eenheid enum. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Specificeert hoeveel een afbeelding wordt geroteerd en de as die wordt gebruikt om de afbeelding te spiegelen. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Biedt de velden die referentiepunten in [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) vertegenwoordigen voor zoeken. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Specificeert of gladstrijken (antialiasing) wordt toegepast op lijnen en krommen en op de randen van gevulde gebieden. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Specificeert de uitlijning van een tekststring ten opzichte van zijn layoutrectangle. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | De enumeratie specificeert hoe cijfers in een string worden vervangen volgens de locale of taal van een gebruiker. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Specificeert de weergave‑ en layoulinformatie voor tekststrings. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Specificeert hoe tekens uit een string worden getrimd die niet volledig in een layoutvorm passen. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Specificeert de kwaliteit van tekstweergave. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Specificeert het type warp‑transformatie dat wordt toegepast. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Specificeert hoe een textuur of verloop wordt getegeld wanneer deze kleiner is dan het gebied dat wordt gevuld. |
