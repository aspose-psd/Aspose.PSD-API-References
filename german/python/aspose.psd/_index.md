---
title: "aspose.psd"
type: docs
weight: 10
url: /de/python-net/aspose.psd/
---


Das Modul ist das Kernstück für verschachtelte Module und die grundlegendsten Objekte, die für die Verarbeitung von Aspose.PSD verwendet werden.

## **Classes**
| **Class** | **Beschreibung** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Definiert ein Mischmuster. Diese Klasse kann nicht geerbt werden. |
| [Brush](/psd/python-net/aspose.psd/brush/) | Die Basispinselklasse. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Enthält die aktuelle Build-Versionsinformation. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Enthält Cache-Einstellungen. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | Die CMYK-Farbe des Pixels. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Hilfsmethoden zur Arbeit mit CMYK-Farbe, dargestellt als vorzeichenbehafteter 32‑Bit‑Integer‑Wert.<br/>            Bietet eine ähnliche API wie die [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) Struktur.<br/>            Sie ist leichter, weil CMYK-Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird.<br/>            Bitte bevorzugen Sie, nach Möglichkeit die statischen Methoden dieser Klasse zu verwenden, anstatt der veralteten<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) Struktur. |
| [Color](/psd/python-net/aspose.psd/color/) | Die Farbe des Pixels. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Definiert Arrays von Farben und Positionen, die zum Interpolieren von Farbmischungen in einem mehrfarbigen Verlauf verwendet werden. Diese Klasse kann nicht geerbt werden. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Definiert eine Zuordnung zum Konvertieren von Farben. Mehrere Methoden der [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) Klasse passen Bildfarben an, indem sie eine Farb-Remap-Tabelle verwenden, die ein Array von [ColorMap](/psd/python-net/aspose.psd/colormap/) Strukturen ist. Nicht vererbbar. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Definiert eine 5 × 5‑Matrix, die die Koordinaten für den RGBA‑Raum enthält. Mehrere Methoden der [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) Klasse passen Bildfarben an, indem sie eine Farbmatrix verwenden. Diese Klasse kann nicht vererbt werden. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Definiert ein Array von Farben, die eine Farbpalette bilden. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Hilfsklasse zur Manipulation von Farbpaletten. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Übersetzt Farben zu und von GDI+‑Color‑Strukturen. Diese Klasse kann nicht vererbt werden. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Kapselt eine benutzerdefinierte, vom Benutzer definierte Linienendkappe. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | Der Datenstrom‑Container. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Stellt ein verwertbares Objekt dar. |
| [Figure](/psd/python-net/aspose.psd/figure/) | Die Figur. Ein Container für Formen. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Hilfsprogramm für die Verarbeitung von Dateistreams. |
| [Font](/psd/python-net/aspose.psd/font/) | Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute. Diese Klasse kann nicht vererbt werden. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Allgemeine Schriftarteinstellungen des Renderers für PSD-Vektorformate. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Stellt die Grafiken gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Stellt eine Reihe verbundener Linien und Kurven dar. Diese Klasse kann nicht vererbt werden. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | Der erweiterte Pufferprozessor. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | Der Pufferprozessor. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | Der Farbkonverter. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | Die Farbpaletten‑Schnittstelle. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | Der Bildersteller. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | Der Bildersteller‑Deskriptor, der die Ersteller‑Eigenschaften spezifiziert. Der Ersteller‑Deskriptor wird verwendet, um die Notwendigkeit zu überwinden<br/>
            jede Bildersteller‑Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | Der Bild‑Deskriptor. Enthält Basiseigenschaften und -methoden für alle anderen Bild‑Deskriptor‑Typen. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | Der Bild‑Exporter. Kann Daten vom internen Aspose.PSD‑Format in ein angegebenes Datenformat exportieren. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Stellt den Bild‑Exporter‑Deskriptor dar. Der Exporter‑Deskriptor wird verwendet, um die Notwendigkeit zu überwinden, jede Exporter‑Instanz<br/>
            im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | Der Bild‑Lader. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | Der Bild‑Lader‑Deskriptor, der die Lader‑Eigenschaften spezifiziert. Der Lader‑Deskriptor wird verwendet, um die Notwendigkeit zu überwinden<br/>
            jede Bild‑Lader‑Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | Der Farbkonverter für indizierte Bildformate. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Stellt eine Schnittstelle für Objekte mit Schlüsseln dar. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Stellt ein Objekt mit Begrenzungen dar. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Stellt eine geordnete Form dar. Eine geordnete Form ist eine kontinuierliche Menge von Punkten mit einem Startpunkt und einem Endpunkt.<br/>            Die kontinuierliche Menge von Punkten, die mittels einer spezifischen Regel verbunden sind. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Entspricht den teilweise geladenen 32‑Bit‑ARGB‑Pixeln. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | Der 64‑Bit‑ARGB‑Pixel‑Lader. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Entspricht den teilweise geladenen Pixeln. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | Der Teillader für Daten. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | Die pasd-Farbpalette |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | Der Rasterbild‑32‑Bit‑ARGB‑Pixel‑Lader. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | Der Rasterbild‑Pixel‑Lader. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | Der Rasterbild‑Rohdaten‑Lader. |
| [Image](/psd/python-net/aspose.psd/image/) | Das Bild ist die Basisklasse für alle Bildtypen. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Ein [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑Objekt enthält Informationen darüber, wie Bitmap‑ und Metafile‑Farben während der Darstellung manipuliert werden. Ein [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑Objekt verwaltet mehrere Farbe‑Anpassungseinstellungen, einschließlich Farb‑Anpassungsmatrizen, Graustufen‑Anpassungsmatrizen, Gamma‑Korrekturwerte, Farb‑Zuordnungstabellen und Farb‑Schwellenwerte. Während der Darstellung können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑Objekt und übergeben den Pfad dieses [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)‑Objekts (zusammen mit dem Pfad eines [Image](/psd/python-net/aspose.psd/image/)) an die DrawImage‑Methode. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Stellt das Registrierungsverzeichnis der Bildersteller dar. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Stellt das Registrierungsverzeichnis der Bildexporteure dar. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Stellt das Registrierungsverzeichnis der Bildlader dar. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | Die Basisoptionen für das Bild. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Klasse für Bildgrößen‑Einstellungen |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Klasse zur Darstellung einer Sequenz von Elementen |
| [License](/psd/python-net/aspose.psd/license/) | Stellt Methoden bereit, um die Komponente zu lizenzieren. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Stellt die Ladeoptionen dar. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Ersetzt die GDI+‑Matrix. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Stellt Methoden bereit, um den gemessenen Schlüssel zu setzen. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Stellt ein nicht generisches Wörterbuch dar. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Nicht generische Liste von Objekten |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | Das Objekt mit Begrenzungen. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Cache für OpenType-Schriften, die im System installiert sind. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | Das Pixel-Datenformat. Dies ist ein unveränderliches Objekt. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | Die Klasse zum Speichern von Bildpixeldaten und deren Begrenzungen. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Ausnahme für Plugin-Lizenz |
| [Point](/psd/python-net/aspose.psd/point/) | Stellt ein geordnetes Paar von ganzzahligen x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Stellt ein geordnetes Paar von Gleitkomma-x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt. Dieses Bild cached Pixeldaten bei Bedarf. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | Die Rohdaten-Einstellungen |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Speichert ein Set von vier Ganzzahlen, die den Ort und die Größe eines Rechtecks darstellen. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Speichert ein Set von vier Gleitkommazahlen, die den Ort und die Größe eines Rechtecks darstellen. |
| [Region](/psd/python-net/aspose.psd/region/) | Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht geerbt werden. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | Die Auflösungseinstellung für Bildspeicheroptionen. |
| [Shape](/psd/python-net/aspose.psd/shape/) | Die Form. Ein kontinuierliches Set von Punkten, die nach einer bestimmten Regel verbunden sind. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Stellt ein Formsegment dar. Ein Segment ist eine Linie oder Kurve, die zwei Punkte verbindet. |
| [Size](/psd/python-net/aspose.psd/size/) | Stellt Größe dar. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Speichert ein geordnetes Paar von Gleitkommazahlen, typischerweise Breite und Höhe eines Rechtecks. |
| [Source](/psd/python-net/aspose.psd/source/) | Die Quelle wird verwendet, um alle relevanten Informationen für eine Objekt-Pipeline zu enthalten. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Stellt einen geteilten Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Stellt einen Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Kapselt Textlayout-Informationen (wie Ausrichtung, Orientierung und Tabulatoren), Anzeige-Manipulationen (wie Ellipsen-Einfügung und nationale Ziffern-Substitution) und OpenType-Funktionen. Diese Klasse kann nicht geerbt werden. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | Das Objekt, das Transparenz unterstützt. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | Das Vektorbild ist die Basisklasse für alle Arten von Vektorbildern. |
## **Enumerations**
| **Enumeration** | **Beschreibung** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Gibt den zu verwendenden Cache-Typ an. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Stellt den verwendeten Zeichensatz dar. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Gibt an, welche Objekte Farbkorrekturinformationen verwenden. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Gibt einzelne Kanäle im CMYK (Cyan, Magenta, Gelb, Schwarz)-Farbraum an. Diese Aufzählung wird von den SetOutputChannel‑Methoden verwendet. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Farbvergleichsmethode zur Anpassung an den nächsten Nachbarn |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Gibt die Arten von Bildern und Farben an, die von den Farb- und Graustufen-Anpassungseinstellungen eines [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) betroffen sind. |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Methoden zur Farbquantisierung |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Gibt den während der Komposition zu verwendenden Qualitätsgrad an. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Gibt den Typ der grafischen Form an, die an beiden Enden jedes Strichs in einer gestrichelten Linie verwendet wird. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Gibt den Stil der mit einem [Pen](/psd/python-net/aspose.psd/pen/) Objekt gezeichneten gestrichelten Linien an. |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | Der Datenwiederherstellungsmodus. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Dithering‑Methode. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | Die Dithering‑Methoden, die zur Steuerung der Farbkonvertierung verwendet werden. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | Eines der unterstützten PSD-Dateiformate. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Gibt an, wie das Innere eines geschlossenen Pfads gefüllt wird. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Gibt die auf Text angewendeten Stilinformationen an. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Gibt die Maßeinheit für die angegebenen Daten an. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Gibt die verschiedenen für [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/) Objekte verfügbaren Muster an. |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Gibt den Anzeigetyp für Tastaturkürzel‑Präfixe an, die sich auf Text beziehen. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Zu verwendende Bildfilter |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | Die [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) Aufzählung gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Gibt die bekannten Systemfarben an. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Gibt die verfügbaren Endstilarten an, mit denen ein [Pen](/psd/python-net/aspose.psd/pen/) Objekt eine Linie abschließen kann. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Gibt an, wie aufeinanderfolgende Linien- oder Kurvensegmente in einer Figur (Unterpfad), die in einem [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt enthalten ist, verbunden werden. |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Gibt die Reihenfolge für Matrix-Transformationsoperationen an. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Gibt das PDF-Konformitätsniveau für die Ausgabedatei an. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Gibt die Ausrichtung eines [Pen](/psd/python-net/aspose.psd/pen/) Objekts in Bezug auf die theoretische, nullbreite Linie an. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Gibt den Fülltyp an, den ein [Pen](/psd/python-net/aspose.psd/pen/) Objekt zum Füllen von Linien verwendet. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | Die tatsächliche Bedeutung des Pixel-Datenformats. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Gibt den Skalierungstyp an. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Auflösungseinheiten‑Enum. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Gibt an, um wie viel ein Bild rotiert wird und welche Achse zum Spiegeln des Bildes verwendet wird. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Stellt die Felder bereit, die Referenzpunkte in [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) für das Suchen darstellen. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Gibt an, ob Glättung (Antialiasing) auf Linien und Kurven sowie die Kanten gefüllter Bereiche angewendet wird. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Gibt die Ausrichtung einer Textzeichenkette relativ zu ihrem Layoutrechteck an. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | Das Aufzählungselement gibt an, wie Ziffern in einer Zeichenkette gemäß der Gebietsschema- oder Spracheinstellung eines Benutzers ersetzt werden. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Gibt die Anzeige- und Layoutinformationen für Textzeichenketten an. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Gibt an, wie Zeichen aus einer Zeichenkette abgeschnitten werden, die nicht vollständig in eine Layoutform passt. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Gibt die Qualität der Textdarstellung an. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Gibt den Typ der angewendeten Verzerrungs-Transformation an. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Gibt an, wie eine Textur oder ein Farbverlauf gekachelt wird, wenn sie kleiner ist als der zu füllende Bereich. |
