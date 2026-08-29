---
title: "Aspose.PSD"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Der Namespace ist das Kernstück für verschachtelte Namespaces und die grundlegendsten Objekte, die für die Verarbeitung von Aspose.PSD verwendet werden."
type: docs
weight: 10
url: /de/net/aspose.psd/
---
{{< psd/tize >}}
Der Namensraum ist das Kernstück für verschachtelte Namensräume und die grundlegendsten Objekte, die für die Verarbeitung von Aspose.PSD verwendet werden.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AggregateException](./aggregateexception/) | Aggregiert mehrere Ausnahmen. |
| [Blend](./blend/) | Definiert ein Mischmuster. Diese Klasse kann nicht abgeleitet werden. |
| [Brush](./brush/) | Die Basispinsel‑Klasse. |
| [BuildVersionInfo](./buildversioninfo/) | Enthält die aktuelle Build‑Versionsinformation. |
| [Cache](./cache/) | Enthält Cache‑Einstellungen. |
| [CmykColorHelper](./cmykcolorhelper/) | Hilfsmethoden zur Arbeit mit CMYK‑Farbe, die als vorzeichenbehafteter 32‑Bit‑Integerwert dargestellt wird. Bietet eine ähnliche API wie die Struktur [`CmykColor`](../aspose.psd/cmykcolor/). Sie ist leichter, weil CMYK‑Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird. Bitte bevorzugen Sie, nach Möglichkeit die statischen Methoden dieser Klasse zu verwenden, anstatt die veraltete Struktur [`CmykColor`](../aspose.psd/cmykcolor/) zu nutzen. |
| [ColorBlend](./colorblend/) | Definiert Arrays von Farben und Positionen, die zum Interpolieren von Farbmischungen in einem mehrfarbigen Verlauf verwendet werden. Diese Klasse kann nicht abgeleitet werden. |
| [ColorMap](./colormap/) | Definiert eine Zuordnung zum Konvertieren von Farben. Mehrere Methoden der Klasse [`ImageAttributes`](../aspose.psd/imageattributes/) passen Bildfarben mithilfe einer Farb‑Remap‑Tabelle an, die ein Array von Strukturen [`ColorMap`](../aspose.psd/colormap/) ist. Nicht vererbbar. |
| [ColorMatrix](./colormatrix/) | Definiert eine 5 × 5‑Matrix, die die Koordinaten für den RGBA‑Raum enthält. Mehrere Methoden der Klasse [`ImageAttributes`](../aspose.psd/imageattributes/) passen Bildfarben mithilfe einer Farbmatrix an. Diese Klasse kann nicht abgeleitet werden. |
| [ColorPalette](./colorpalette/) | Definiert ein Array von Farben, das eine Farbpalette bildet. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar. |
| [ColorPaletteHelper](./colorpalettehelper/) | Hilfsklasse zur Manipulation von Farbpaletten. |
| [ColorTranslator](./colortranslator/) | Übersetzt Farben zu und von GDI+ Color-Strukturen. Diese Klasse kann nicht abgeleitet werden. |
| [CompositeException](./compositeexception/) | Die zusammengesetzte Ausnahme |
| [CustomLineCap](./customlinecap/) | Kapselt ein benutzerdefiniertes, vom Benutzer definiertes Linienende. |
| [DataStreamSupporter](./datastreamsupporter/) | Der Datenstrom-Container. |
| [DisposableObject](./disposableobject/) | Stellt ein freigebbares Objekt dar. |
| [Figure](./figure/) | Die Figur. Ein Container für Formen. |
| [FileStreamContainer](./filestreamcontainer/) | Hilfsmittel für die Verarbeitung von Dateistreams. |
| [Font](./font/) | Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute. Diese Klasse kann nicht abgeleitet werden. |
| [FontSettings](./fontsettings/) | Allgemeine Schriftarteinstellungen des Renderers für PSD-Vektorformate. |
| [Graphics](./graphics/) | Stellt die Grafik gemäß der im aktuellen Assembly verwendeten Grafik-Engine dar. |
| [GraphicsPath](./graphicspath/) | Stellt eine Reihe verbundener Linien und Kurven dar. Diese Klasse kann nicht abgeleitet werden. |
| [Image](./image/) | Das Bild ist die Basisklasse für alle Bildtypen. |
| [ImageAttributes](./imageattributes/) | Ein [`ImageAttributes`](../aspose.psd/imageattributes/)-Objekt enthält Informationen darüber, wie Bitmap‑ und Metadatei‑Farben während des Renderns manipuliert werden. Ein [`ImageAttributes`](../aspose.psd/imageattributes/)-Objekt verwaltet mehrere Farbkorrektureinstellungen, einschließlich Farbkorrektur‑Matrizen, Graustufen‑Korrektur‑Matrizen, Gamma‑Korrektur‑Werten, Farb‑Zuordnungstabellen und Farb‑Schwellenwerten. Beim Rendern können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein [`ImageAttributes`](../aspose.psd/imageattributes/)-Objekt und übergeben den Pfad dieses [`ImageAttributes`](../aspose.psd/imageattributes/)-Objekts (zusammen mit dem Pfad eines [`Image`](../aspose.psd/image/))-Objekts an die DrawImage‑Methode. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | Stellt das Register der Bild-Ersteller dar. |
| [ImageExportersRegistry](./imageexportersregistry/) | Stellt das Register der Bild-Exportierer dar. |
| [ImageLoadersRegistry](./imageloadersregistry/) | Stellt das Register der Bild‑Lader dar. |
| [ImageOptionsBase](./imageoptionsbase/) | Die Basisoptionen für das Bild. |
| [ImageResizeSettings](./imageresizesettings/) | Klasse für Bildgrößen‑Einstellungen |
| [IntRange](./intrange/) | Klasse zur Darstellung einer Sequenz von Elementen |
| [License](./license/) | Stellt Methoden zur Lizenzierung der Komponente bereit. |
| [LoadOptions](./loadoptions/) | Stellt die Ladeoptionen dar. |
| [Matrix](./matrix/) | Ersetzt die GDI+ Matrix. |
| [Metered](./metered/) | Stellt Methoden zum Setzen des gemessenen Schlüssels bereit. |
| [NonGenericDictionary](./nongenericdictionary/) | Stellt ein nicht generisches Wörterbuch dar. |
| [NonGenericList](./nongenericlist/) | Nicht generische Liste von Objekten |
| [ObjectWithBounds](./objectwithbounds/) | Das Objekt mit Begrenzungen. |
| [OpenTypeFontsCache](./opentypefontscache/) | Cache für OpenType-Schriften, die im System installiert sind. |
| [Pen](./pen/) | Definiert ein Objekt, das zum Zeichnen von Linien, Kurven und Figuren verwendet wird. |
| [PixelDataFormat](./pixeldataformat/) | Das Pixel-Datenformat. Dies ist ein unveränderliches Objekt. |
| [PixelsData](./pixelsdata/) | Die Klasse zum Speichern von Bildpixeldaten und deren Begrenzungen. |
| [PluginLicenseException](./pluginlicenseexception/) | Ausnahme für Plugin-Lizenz. |
| [ProgressEventHandler](./progresseventhandler/) | Referenz zur Fortschritt-Ereignis-Handler-Funktion. |
| [RasterCachedImage](./rastercachedimage/) | Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt. Dieses Bild cached Pixeldaten bei Bedarf. |
| [RasterImage](./rasterimage/) | Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt. |
| [RawDataSettings](./rawdatasettings/) | Die Rohdaten-Einstellungen |
| [Region](./region/) | Beschreibt das Innere einer Grafikform, die aus Rechtecken und Pfaden besteht. Diese Klasse kann nicht vererbt werden. |
| [ResolutionSetting](./resolutionsetting/) | Die Auflösungseinstellung für Bildspeicheroptionen. |
| [Shape](./shape/) | Die Form. Eine kontinuierliche Menge von Punkten, die nach einer bestimmten Regel verbunden sind. |
| [ShapeSegment](./shapesegment/) | Stellt ein Formsegment dar. Ein Segment ist eine Linie oder Kurve, die zwei Punkte verbindet. |
| [Source](./source/) | Die Quelle wird verwendet, um alle relevanten Informationen für eine Objekt-Pipeline zu enthalten. |
| [SplitStreamContainer](./splitstreamcontainer/) | Stellt einen geteilten Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt. |
| [StreamContainer](./streamcontainer/) | Stellt einen Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt. |
| [StringFormat](./stringformat/) | Kapselt Textlayout-Informationen (wie Ausrichtung, Orientierung und Tabulatoren), Anzeige-Manipulationen (wie Ellipsen-Einfügung und nationale Ziffernersetzung) und OpenType-Funktionen. Diese Klasse kann nicht vererbt werden. |
| [TransparencySupporter](./transparencysupporter/) | Das Objekt, das Transparenz unterstützt. |
| [VectorImage](./vectorimage/) | Das Vektorbild ist die Basisklasse für alle Arten von Vektorbildern. |
## Structures

| Struktur | Beschreibung |
| --- | --- |
| [CmykColor](./cmykcolor/) | Die CMYK-Farbe des Pixels. |
| [Color](./color/) | Die Farbe des Pixels. |
| [Point](./point/) | Stellt ein geordnetes Paar von ganzzahligen x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert. |
| [PointF](./pointf/) | Stellt ein geordnetes Paar von Gleitkomma-x- und y-Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert. |
| [Rectangle](./rectangle/) | Speichert ein Set von vier Ganzzahlen, das die Position und Größe eines Rechtecks darstellt. |
| [RectangleF](./rectanglef/) | Speichert ein Set von vier Gleitkommazahlen, das die Position und Größe eines Rechtecks darstellt. |
| [Size](./size/) | Stellt die Größe dar. |
| [SizeF](./sizef/) | Speichert ein geordnetes Paar von Gleitkommazahlen, typischerweise die Breite und Höhe eines Rechtecks. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | Der erweiterte Pufferprozessor. |
| [IBufferProcessor](./ibufferprocessor/) | Der Pufferprozessor. |
| [IColorConverter](./icolorconverter/) | Der Farbkonverter. |
| [IColorPalette](./icolorpalette/) | Die Schnittstelle für Farbpaletten. |
| [IImageCreator](./iimagecreator/) | Der Bildgenerator. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | Der Bildgenerator-Deskriptor, der die Eigenschaften des Erstellers angibt. Der Ersteller-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen, jede Bildgenerator-Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IImageDescriptor](./iimagedescriptor/) | Der Bild-Deskriptor. Enthält Basiseigenschaften und -methoden für alle anderen Bild-Deskriptor-Typen. |
| [IImageExporter](./iimageexporter/) | Der Bild-Exporter. Kann Daten vom internen Aspose.PSD-Format in ein angegebenes Datenformat exportieren. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | Stellt den Bild-Exporter-Deskriptor dar. Der Exporter-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen, jede Exporter-Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IImageLoader](./iimageloader/) | Der Bild-Loader. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | Der Bild-Loader-Deskriptor, der die Loader-Eigenschaften angibt. Der Loader-Deskriptor wird verwendet, um die Notwendigkeit zu umgehen, jede Bild-Loader-Instanz im Speicher zu halten und Probleme mit Multithreading zu vermeiden. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | Der Farbkonverter für indizierte Bildformate. |
| [IKeyedObject](./ikeyedobject/) | Stellt eine Schnittstelle für Objekte mit Schlüsseln dar. |
| [IObjectWithBounds](./iobjectwithbounds/) | Stellt ein Objekt mit Begrenzungen dar. |
| [IOrderedShape](./iorderedshape/) | Stellt eine geordnete Form dar. Eine geordnete Form ist eine kontinuierliche Menge von Punkten mit einem Start- und Endpunkt. Die kontinuierliche Punktmenge ist mittels einer spezifischen Regel verbunden. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | Entspricht den teilweise geladenen 32‑Bit‑ARGB‑Pixeln. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | Der 64‑Bit‑ARGB‑Pixel‑Loader. |
| [IPartialPixelLoader](./ipartialpixelloader/) | Entspricht den teilweise geladenen Pixeln. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | Der Teil-Daten‑Loader. |
| [IPsdColorPalette](./ipsdcolorpalette/) | Die pasd-Farbpalette |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | Der Rasterbild‑32‑Bit‑ARGB‑Pixel‑Loader. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | Der Rasterbild-Pixel-Lader. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | Der Rasterbild-Rohdaten-Lader. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [CacheType](./cachetype/) | Gibt den zu verwendenden Cache-Typ an. |
| [CharacterSet](./characterset/) | Stellt den verwendeten Zeichensatz dar. |
| [ColorAdjustType](./coloradjusttype/) | Gibt an, welche Objekte Farbanpassungsinformationen verwenden. |
| [ColorChannelFlag](./colorchannelflag/) | Gibt einzelne Kanäle im CMYK (cyan, magenta, yellow, black)-Farbraum an. Diese Aufzählung wird von den SetOutputChannel-Methoden verwendet. |
| [ColorCompareMethod](./colorcomparemethod/) | Farbvergleichsmethode zur Anpassung an den nächsten Nachbarn |
| [ColorMatrixFlag](./colormatrixflag/) | Gibt die Bild- und Farbtypen an, die von den Farb- und Graustufen-Anpassungseinstellungen eines [`ImageAttributes`](../aspose.psd/imageattributes/) betroffen sind. |
| [ColorQuantizationMethod](./colorquantizationmethod/) | Methoden zur Farbquantisierung |
| [CompositingQuality](./compositingquality/) | Gibt die während des Compositings zu verwendende Qualitätsstufe an. |
| [DashCap](./dashcap/) | Gibt den Typ der grafischen Form an, die an beiden Enden jedes Strichs in einer gestrichelten Linie verwendet wird. |
| [DashStyle](./dashstyle/) | Gibt den Stil der mit einem [`Pen`](../aspose.psd/pen/) Objekt gezeichneten gestrichelten Linien an. |
| [DataRecoveryMode](./datarecoverymode/) | Der Datenwiederherstellungsmodus. |
| [DitheringMethod](./ditheringmethod/) | Dithering-Methode. |
| [DitheringMethods](./ditheringmethods/) | Die Dithering-Methoden, die zur Steuerung der Farbkonvertierung verwendet werden. |
| [FileFormat](./fileformat/) | Eines der unterstützten PSD-Dateiformate. |
| [FillMode](./fillmode/) | Gibt an, wie das Innere eines geschlossenen Pfads gefüllt wird. |
| [FontStyle](./fontstyle/) | Gibt die auf Text angewendeten Stilinformationen an. |
| [GraphicsUnit](./graphicsunit/) | Gibt die Maßeinheit für die angegebenen Daten an. |
| [HatchStyle](./hatchstyle/) | Gibt die verschiedenen für [`HatchBrush`](../aspose.psd.brushes/hatchbrush/) Objekte verfügbaren Muster an. |
| [HotkeyPrefix](./hotkeyprefix/) | Gibt den Anzeigetyp für Tastenkombinationspräfixe an, die sich auf Text beziehen. |
| [ImageFilterType](./imagefiltertype/) | Zu verwendende Bildfilter |
| [InterpolationMode](./interpolationmode/) | Die [`InterpolationMode`](../aspose.psd/interpolationmode/) Aufzählung gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden. |
| [KnownColor](./knowncolor/) | Gibt die bekannten Systemfarben an. |
| [LineCap](./linecap/) | Gibt die verfügbaren Endstilarten an, mit denen ein [`Pen`](../aspose.psd/pen/) Objekt eine Linie beenden kann. |
| [LineJoin](./linejoin/) | Gibt an, wie aufeinanderfolgende Linien- oder Kurvensegmente in einer Figur (Unterpfad), die in einem [`GraphicsPath`](../aspose.psd/graphicspath/) Objekt enthalten ist, verbunden werden. |
| [MatrixOrder](./matrixorder/) | Gibt die Reihenfolge für Matrix-Transformationsoperationen an. |
| [PdfComplianceVersion](./pdfcomplianceversion/) | Gibt das PDF-Konformitätsniveau für die Ausgabedatei an. |
| [PenAlignment](./penalignment/) | Gibt die Ausrichtung eines [`Pen`](../aspose.psd/pen/) Objekts in Bezug auf die theoretische, nullbreite Linie an. |
| [PenType](./pentype/) | Gibt den Fülltyp an, den ein [`Pen`](../aspose.psd/pen/) Objekt zum Füllen von Linien verwendet. |
| [PixelFormat](./pixelformat/) | Die tatsächliche Bedeutung des Pixeldatenformats. |
| [ResizeType](./resizetype/) | Gibt den Skalierungstyp an. |
| [ResolutionUnit](./resolutionunit/) | Auflösungseinheiten-Enum. |
| [RotateFlipType](./rotatefliptype/) | Gibt an, um wie viel ein Bild rotiert wird und welche Achse zum Spiegeln des Bildes verwendet wird. |
| [SeekOrigin](./seekorigin/) | Stellt die Felder bereit, die Referenzpunkte in [`StreamContainer`](../aspose.psd/streamcontainer/) für das Suchen darstellen. |
| [SmoothingMode](./smoothingmode/) | Gibt an, ob Glättung (Antialiasing) auf Linien und Kurven sowie die Kanten gefüllter Bereiche angewendet wird. |
| [StringAlignment](./stringalignment/) | Gibt die Ausrichtung einer Textzeichenfolge relativ zu ihrem Layoutrechteck an. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | Die Aufzählung gibt an, wie Ziffern in einer Zeichenfolge gemäß der Gebietsschema- oder Spracheinstellung eines Benutzers ersetzt werden. |
| [StringFormatFlags](./stringformatflags/) | Gibt die Anzeige- und Layoutinformationen für Textzeichenfolgen an. |
| [StringTrimming](./stringtrimming/) | Gibt an, wie Zeichen aus einer Zeichenfolge abgeschnitten werden, die nicht vollständig in eine Layoutform passt. |
| [TextRenderingHint](./textrenderinghint/) | Gibt die Qualität der Textdarstellung an. |
| [WarpMode](./warpmode/) | Gibt den Typ der angewendeten Verzerrungstransformation an. |
| [WrapMode](./wrapmode/) | Gibt an, wie eine Textur oder ein Farbverlauf gekachelt wird, wenn sie kleiner ist als der zu füllende Bereich. |


