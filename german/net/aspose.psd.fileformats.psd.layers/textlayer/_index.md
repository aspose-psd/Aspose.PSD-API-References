---
title: Class TextLayer
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.TextLayer klas. Die Textebenenklasse
type: docs
weight: 3560
url: /de/net/aspose.psd.fileformats.psd.layers/textlayer/
---
## TextLayer class

Die Textebenenklasse

```csharp
public class TextLayer : Layer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Ruft die Mischoptionen ab. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Ruft den Mischmodusschlüssel ab oder legt ihn fest. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Ruft die Mischmodus-Signatur ab. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Ruft die Position der untersten Ebene ab oder legt sie fest. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Ruft die Kanalinformationen ab oder legt sie fest. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Ruft die Anzahl der Kanäle der Ebene ab. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Holt oder setzt das Layer-Clipping. 0 = Basis, 1 = Nicht-Basis. |
| [Container](../../aspose.psd/image/container/) { get; } | Ruft die ab[`Image`](../../aspose.psd/image/) Container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ruft den Datenstrom des Objekts ab. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Ruft den Anzeigenamen der Ebene ab oder legt ihn fest. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Ruft die Schicht-Zusatzinformationslänge in Bytes ab. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Ruft einen Wert von Dateiformat ab |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Ruft den Ebenenfüller ab oder legt ihn fest. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Ruft die Deckkraft der Füllung ab oder legt sie fest. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Ruft die Layer-Flags ab oder setzt sie. Bit 0 = Transparenz geschützt; Bit 1 = sichtbar; Bit 2 = veraltet; Bit 3 = 1 für Photoshop 5.0 und höher, gibt an, ob Bit 4 nützliche Informationen enthält; Bit 4 = Pixeldaten sind für das Erscheinungsbild des Dokuments irrelevant. |
| [Font](../../aspose.psd.fileformats.psd.layers/textlayer/font/) { get; } | Ruft die Schriftart ab. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz alpha hat. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Ruft einen Wert ab, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Ruft die Bildhöhe ab. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Ruft die Deckkraft dieses Bildes ab. |
| [InnerText](../../aspose.psd.fileformats.psd.layers/textlayer/innertext/) { get; } | Ruft den Text der Ebene ab |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Ebene sichtbar ist |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz in der Gruppe sichtbar ist (Wenn die Ebene nicht in der Gruppe ist, bedeutet dies die Stammgruppe). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Ruft die Daten der Ebenenüberblendungsbereiche ab oder legt sie fest. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Ruft die Uhrzeit der Erstellung des Layers ab oder legt sie fest. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Ruft die Layer-Sperre ab oder setzt sie. Beachten Sie, dass wenn das Flag LayerFlags.TransparencyProtected gesetzt ist, es durch das Layer-Sperr-Flag überschrieben wird. Um das LayerFlags.TransparencyProtected-Flag zurückzugeben, muss die Layer-Option layer.Flags &#x7C;= LayerFlags.TransparencyProtected angewendet werden |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Ruft die Ebenenmaskendaten ab oder legt sie fest. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Ruft die Ebenenoptionen ab. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Holt oder setzt die Position der linken Ebene. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Ruft die Gesamtschichtlänge in Bytes ab. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Ruft den Ebenennamen ab oder legt ihn fest. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Holt oder setzt die Deckkraft der Ebene. 0 = transparent, 255 = undurchsichtig. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Ruft den benutzerdefinierten Farbkonverter ab oder legt ihn fest |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Ruft das Rohdatenformat ab. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Ruft die aktuellen Rohdateneinstellungen ab. Beachten Sie, dass bei Verwendung dieser Einstellungen die Daten ohne Konvertierung geladen werden. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ruft den Fallback-Index ab oder legt ihn fest, der verwendet werden soll, wenn der Palettenindex außerhalb der Grenzen liegt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Holt oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ruft die rohe Zeilengröße in Bytes ab. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Ruft die Layer-Ressourcen ab oder legt sie fest. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Holt oder setzt die richtige Layerposition. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Holt oder setzt die Hervorhebung der Dekorationsblattfarbe in der Ebenenliste |
| [Size](../../aspose.psd/image/size/) { get; } | Ruft die Bildgröße ab. |
| [Text](../../aspose.psd.fileformats.psd.layers/textlayer/text/) { get; } | Ruft den Text ab. |
| [TextBoundBox](../../aspose.psd.fileformats.psd.layers/textlayer/textboundbox/) { get; set; } | Ruft das Textbegrenzungsfeld ab oder legt es fest. |
| [TextColor](../../aspose.psd.fileformats.psd.layers/textlayer/textcolor/) { get; } | Ruft die Farbe des Textes ab. |
| [TextData](../../aspose.psd.fileformats.psd.layers/textlayer/textdata/) { get; } | Ruft die Textteile ab. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Ruft die Position der obersten Ebene ab oder legt sie fest. |
| [TransformMatrix](../../aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/) { get; set; } | Holt oder setzt die Transformationsmatrix |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Ruft die transparente Farbe des Bildes ab. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Ruft die Bildbreite ab. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Ruft die XMP-Metadaten ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Fügt die Maske der aktuellen Ebene hinzu. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Anpassen einer Helligkeit für das Bild. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Bildkontrast |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Bild zuschneiden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Zeichnet das Bild auf Ebene. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| [GetFonts](../../aspose.psd.fileformats.psd.layers/textlayer/getfonts/)() | Ruft den Schriftsatz der Textebene ab. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Gibt einen Hash-Code für diese Instanz zurück. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.psd/datastreamsupporter/save/) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.psd/image/save/)Methode als zweiten Parameter. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ruft ein Bildpixel ab. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ruft den Schräglaufwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schräglaufwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformation eines Bildes in seine Graustufendarstellung |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Lädt 32-Bit-ARGB-Pixel. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Lädt 64-Bit-ARGB-Pixel. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Lädt Pixel im CMYK-Format. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32-Bit-ARGB-Pixel teilweise nach Paketen. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise nach Paketen. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Führt die Ebene mit der angegebenen Ebene zusammen |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Und[`Rotate`](../../aspose.psd/rasterimage/rotate/) Methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Und[`Rotate`](../../aspose.psd/rasterimage/rotate/) Methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.psd.fileformats.psd.layers/textlayer/resize/#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ändert die Breite proportional. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Bild um die Mitte drehen. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.psd/image/save/)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Speichert die 32-Bit-ARGB-Pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Speichert die Pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Speichert die Pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Speichert die Rohdaten. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Legt ein 32-Bit-ARGB-Bildpixel für die angegebene Position fest. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Legt die Bildpalette fest. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Legt die Auflösung dafür fest[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Erstellt eine flache Kopie der aktuellen Ebene. Bitte[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) zur Erklärung. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konvertiert Rasterbild in Bitmap. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext)(string) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_1)(string, Color) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_6)(string, float) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_2)(string, Point) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_7)(string, float, Color) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_3)(string, Point, Color) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_4)(string, Point, float) | Aktualisiert den Text. |
| [UpdateText](../../aspose.psd.fileformats.psd.layers/textlayer/updatetext/#updatetext_5)(string, Point, float, Color) | Aktualisiert den Text. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |

### Beispiele

Das folgende Beispiel zeigt, dass die Textausrichtung durch ITextPortion für rechts-nach-links-Sprachen ordnungsgemäß funktioniert.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

Der folgende Code zeigt, wie Sie die Schriftgröße für einen beliebigen Textabschnitt in der Textebene abrufen.

```csharp
[C#]

// Falsche Schriftgröße extrahiert 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Alte API (mit der Schriftart des ersten Absatzes)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Überprüfen der Basisschriftgröße
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfen der tatsächlichen Schriftgröße
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Neue API (Eine Textebene kann beliebig viele Schriftgrößen enthalten)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Überprüfen der Schriftgröße des Basisteils
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfung der Schriftgröße des realen Teils
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Siehe auch

* class [Layer](../layer/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Montage [Aspose.PSD](../../)


