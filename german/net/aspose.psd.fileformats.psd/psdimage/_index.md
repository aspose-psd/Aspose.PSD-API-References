---
title: Class PsdImage
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.PsdImage klas. Definiert die PsdImageKlasse die die Möglichkeit bietet PSDDateien zu laden zu bearbeiten zu speichern sowie Eigenschaften zu aktualisieren Wasserzeichen hinzuzufügen Grafikoperationen durchzuführen oder ein Dateiformat in ein anderes zu konvertieren. Aspose.PSD unterstützt den Import als Ebene und den Export in die folgende Formate Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb sowie Export nach Pdf mit wählbarem Text
type: docs
weight: 3590
url: /de/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Definiert die PsdImage-Klasse, die die Möglichkeit bietet, PSD-Dateien zu laden, zu bearbeiten, zu speichern sowie Eigenschaften zu aktualisieren, Wasserzeichen hinzuzufügen, Grafikoperationen durchzuführen oder ein Dateiformat in ein anderes zu konvertieren. Aspose.PSD unterstützt den Import als Ebene und den Export in die folgende Formate: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb sowie Export nach Pdf mit wählbarem Text

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Initialisiert eine neue Instanz von`PsdImage`Klasse aus vorhandenem Rasterbild (kein PSD-Bild) mit RGB-Farbmodus mit 4 Kanälen 8 Bit/Kanal und ohne Komprimierung. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Initialisiert eine neue Instanz von`PsdImage` Klasse aus dem angegebenen Pfad vom Rasterbild (kein PSD-Bild im Stream). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – RGB, 4 Kanäle, 8 Bit pro Kanal, Komprimierung – Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Initialisiert eine neue Instanz von`PsdImage` Klasse aus dem angegebenen Pfad aus dem Rasterbild (nicht das PSD-Bild im Pfad). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – RGB, 4 Kanäle, 8 Bit pro Kanal, Komprimierung – Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Initialisiert eine neue Instanz von`PsdImage` Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD-Bild zu initialisieren. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz von`PsdImage` Klasse aus vorhandenem Rasterbild (nicht PSD-Bild) mit Konstruktorparametern. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz von`PsdImage` Klasse aus dem angegebenen Pfad vom Rasterbild (kein PSD-Bild im Stream) mit Konstruktorparametern. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz von`PsdImage` Klasse aus dem angegebenen Pfad aus dem Rasterbild (kein PSD-Bild im Pfad) mit Konstruktorparametern. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz von`PsdImage` Klasse mit angegebener Breite, Höhe, Paletter, Farbmodus, Kanalanzahl und Kanalbitlänge und angegebenen Komprimierungsmodusparametern. Wird verwendet, um ein leeres PSD-Bild zu initialisieren. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Ruft die aktive Ebene ab oder legt sie fest. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Ruft die Bits pro Kanal ab. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Ruft die Anzahl der PSD-Kanäle ab. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Ruft das CMYK-Farbprofil für CMYK-PSD-Bilder ab oder legt es fest. Muss für eine korrekte Farbkonvertierung mit RgbColorProfile gekoppelt sein. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Ruft den Farbmodus ab oder legt ihn fest. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Ruft die Komprimierungsmethode ab. |
| [Container](../../aspose.psd/image/container/) { get; } | Ruft die ab[`Image`](../../aspose.psd/image/) Container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Ruft einen Wert von Dateiformat ab |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Ruft den globalen Winkel ab oder legt ihn fest. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Ruft die Informationen der globalen Ebenenmaske ab. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Ruft die globalen Layer-Ressourcen ab oder legt sie fest. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Ruft das GRAU (monochrom) Farbprofil für Graustufen-PSD-Bilder ab oder legt es fest. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Ruft einen Wert ab, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Ruft die Bildhöhe ab. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Ruft die Deckkraft dieses Bildes ab. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Ruft die PSD-Bildressourcen ab oder legt sie fest. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Ruft einen Wert ab, der angibt, ob das PSD-Bild reduziert wird. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Ruft die PSD-Ebenen ab oder legt sie fest. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Ruft den Manager für verknüpfte Ebenen ab. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Ruft den benutzerdefinierten Farbkonverter ab oder legt ihn fest |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Ruft das Rohdatenformat ab. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Ruft die aktuellen Rohdateneinstellungen ab. Beachten Sie, dass bei Verwendung dieser Einstellungen die Daten ohne Konvertierung geladen werden. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ruft den Fallback-Index ab oder legt ihn fest, der verwendet werden soll, wenn der Palettenindex außerhalb der Grenzen liegt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Holt oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Ruft die rohe Zeilengröße in Bytes ab. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Ruft das RGB-Farbprofil für CMYK-PSD-Bilder ab oder legt es fest. Muss für eine korrekte Farbkonvertierung mit CmykColorProfile gekoppelt sein. |
| [Size](../../aspose.psd/image/size/) { get; } | Ruft die Bildgröße ab. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Ruft den Smart-Objekt-Anbieter ab. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Ruft die transparente Farbe des Bildes ab. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Ruft die Version ab oder legt sie fest. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Ruft die Bildbreite ab. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Ruft die XMP-Metadaten ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Fügt die Schwarzweiß-Anpassungsebene hinzu. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Fügt die Helligkeits-/Kontrasteinstellungsebene hinzu. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Fügt die Kanalmixer-Einstellungsebene mit Standardparametern hinzu |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Fügt die Farbbalance-Anpassungsebene hinzu. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Fügt die Ebene „Kurvenanpassung“ hinzu. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Fügt die Belichtungsanpassungsebene hinzu. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Fügt die Einstellungsebene für Farbton/Sättigung hinzu. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Fügt eine Invertierungsebene hinzu. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Fügt die Ebene hinzu. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Fügt die Ebenengruppe hinzu. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Fügt die Ebenen-Anpassungsebene hinzu. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Fügt die PhotoFilter-Ebene hinzu. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Fügt eine neue reguläre Ebene hinzu. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Fügt eine neue Textebene hinzu. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Fügt die Dynamik-Einstellungsebene hinzu. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Anpassen einer Helligkeit für das Bild. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Bildkontrast |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Konvertiert dieses Bildformat in das in den Optionen angegebene. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Bild zuschneiden. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Flacht alle Ebenen ab. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.psd/datastreamsupporter/save/) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.psd/image/save/)Methode als zweiten Parameter. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ruft ein Bildpixel ab. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ruft den Schräglaufwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schräglaufwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformation eines Bildes in seine Graustufendarstellung |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Lädt 32-Bit-ARGB-Pixel. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Lädt 64-Bit-ARGB-Pixel. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Lädt Pixel im CMYK-Format. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32-Bit-ARGB-Pixel teilweise nach Paketen. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise nach Paketen. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Führt die Ebenen zusammen. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Und[`Rotate`](../../aspose.psd/rasterimage/rotate/) Methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Und[`Rotate`](../../aspose.psd/rasterimage/rotate/) Methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändert die Breite proportional. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Bild um die Mitte drehen. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.psd/image/save/)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Speichert die 32-Bit-ARGB-Pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Speichert die Pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Speichert die Pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Speichert die Rohdaten. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Legt ein 32-Bit-ARGB-Bildpixel für die angegebene Position fest. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Legt die Bildpalette fest. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Legt die Auflösung dafür fest[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konvertiert Rasterbild in Bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Die Standard-PSD-Version. |

### Beispiele

Der folgende Code demonstriert die Möglichkeit, das Bild um einen bestimmten Winkelwert zu drehen.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Ganzes Bild rotiert
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Layer rotiert
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Siehe auch

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namensraum [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Montage [Aspose.PSD](../../)


