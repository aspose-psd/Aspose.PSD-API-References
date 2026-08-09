---
title: "Klasse PsdImage"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.PsdImage Klasse. Definiert die PsdImage‑Klasse, die die Möglichkeit bietet, PSD‑Dateien zu laden, zu bearbeiten und zu speichern sowie Eigenschaften zu aktualisieren, Wasserzeichen hinzuzufügen, Grafikoperationen durchzuführen oder ein Dateiformat in ein anderes zu konvertieren. Aspose.PSD unterstützt den Import als Ebene und den Export in die folgenden Formate: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb sowie den Export nach Pdf mit auswählbarem Text."
type: docs
weight: 4050
url: /de/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Definiert die Klasse PsdImage, die die Möglichkeit bietet, PSD-Dateien zu laden, zu bearbeiten und zu speichern sowie Eigenschaften zu aktualisieren, Wasserzeichen hinzuzufügen, Grafikoperationen durchzuführen oder ein Dateiformat in ein anderes zu konvertieren. Aspose.PSD unterstützt den Import als Layer und den Export in die folgenden Formate: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb sowie den Export nach Pdf mit auswählbarem Text.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse aus einem vorhandenen Rasterbild (kein PSD‑Bild) mit RGB‑Farbmodus, 4 Kanälen, 8 Bit/Kanal und ohne Kompression. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Stream). Wird verwendet, um ein PSD‑Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Pfad). Wird verwendet, um ein PSD‑Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse aus einem vorhandenen Rasterbild (kein PSD‑Bild) mit Konstruktorparametern. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Stream) mit Konstruktorparametern. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Pfad) mit Konstruktorparametern. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initialisiert eine neue Instanz der `PsdImage`‑Klasse mit angegebenen Breite, Höhe, Palette, Farbmodus, Kanalanzahl und Kanal-Bit-Länge sowie den angegebenen Kompressionsmodus-Parametern. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Liest oder setzt die aktive Ebene. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Liest die Bits pro Kanal. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Liest die Bit‑pro‑Pixel‑Anzahl des Bildes. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Liest die Bildgrenzen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Liest die Anzahl der PSD-Kanäle. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Liest oder setzt das CMYK-Farbprofil für CMYK-PSD-Bilder. Muss zusammen mit RgbColorProfile für korrekte Farbkonvertierung verwendet werden. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Liest oder setzt den Farbmodus. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Liest die Komprimierungsmethode. |
| [Container](../../aspose.psd/image/container/) { get; } | Liest den [`Image`](../../aspose.psd/image/)‑Container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Liest den Datenstrom des Objekts. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Liefert einen Wert des Dateiformats |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Liest oder setzt den globalen Winkel. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Liest die Informationen zur globalen Ebenenmaske. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Liest oder setzt die globalen Ebenenressourcen. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Liest oder setzt das GRAY (monochrom) Farbprofil für Graustufen-PSD-Bilder. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Liefert einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Liefert die Bildhöhe. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Liest oder setzt die horizontale Auflösung dieses `PsdImage` in Pixel pro Zoll. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Liefert die Deckkraft dieses Bildes. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Liest oder setzt die PSD-Bildressourcen. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Liefert oder setzt den Unterbrechungsmonitor. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Liefert einen Wert, der angibt, ob Bilddaten derzeit im Cache sind. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Liest einen Wert, der angibt, ob das PSD-Bild abgeflacht ist. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Liefert einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Liest oder setzt die PSD-Ebenen. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Liest den Manager für verknüpfte Ebenen. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvervielfacht werden müssen. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Liest oder setzt den benutzerdefinierten Farbkonverter |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Liest das Rohdatenformat. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Liest die aktuellen Rohdaten-Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Liest oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Liest die Rohzeilengröße in Bytes. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Liest oder setzt das RGB-Farbprofil für CMYK-PSD-Bilder. Muss zusammen mit CmykColorProfile für korrekte Farbkonvertierung verwendet werden. |
| [Size](../../aspose.psd/image/size/) { get; } | Liest die Bildgröße. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Liest den Anbieter für intelligente Objekte. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Liest die [`Timeline`](./timeline/) dieses `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Liest die transparente Bildfarbe. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Ruft die Version ab oder legt sie fest. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Liest oder setzt die vertikale Auflösung dieses `PsdImage` in Pixel pro Zoll. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Liest die Bildbreite. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Liest oder setzt die XMP-Metadaten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Fügt die Schwarz‑Weiß‑Anpassungsebene hinzu. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Fügt die Helligkeit/Kontrast‑Anpassungsebene hinzu. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Fügt die Kanalmixer‑Anpassungsebene mit Standardparametern hinzu |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Fügt die Farbtonwertausgleich‑Anpassungsebene hinzu. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Fügt die Kurven‑Anpassungsebene hinzu. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Fügt die Belichtungs‑Anpassungsebene hinzu. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Fügt die GradientMap‑Anpassungsebene hinzu. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Fügt die Farbton/Sättigung-Anpassungsebene hinzu. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Fügt eine Invertierungs-Anpassungsebene hinzu. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Fügt die Ebene hinzu. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Fügt die Ebenengruppe hinzu. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Fügt die Levels-Anpassungsebene hinzu. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Fügt die PhotoFilter-Ebene hinzu. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Fügt die Posterize-Anpassungsebene hinzu. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Fügt eine neue reguläre Ebene hinzu. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Fügt die selektive Farb-Anpassungsebene hinzu. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Füge leere Shape-Ebene hinzu. Ohne Pfade. Sie sollten vor dem Speichern zur Shape-Ebene hinzugefügt werden. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Fügt eine neue Text-Ebene hinzu. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Fügt die Schwellenwert-Anpassungsebene hinzu. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Fügt die Vibrance-Anpassungsebene hinzu. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Anpassung der Helligkeit für das Bild. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Bildkontrastierung |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisierung eines Bildes mit Otsu‑Schwellenwertbestimmung |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) durchgeführt werden. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Konvertiert dieses Bildformat in das in den Optionen angegebene. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Zuschneiden des Bildes. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Führt Dithering am aktuellen Bild aus. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Führt Dithering am aktuellen Bild aus. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Flacht alle Ebenen ab. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Liefert ein 32‑Bit‑ARGB‑Pixel eines Bildes. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Liefert die Standardoptionen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Liefert das Standard‑Pixel‑Array unter Verwendung eines partiellen Pixel‑Laders. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Liefert das Standard‑Rohdaten‑Array. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Liefert das Standard‑Rohdaten‑Array unter Verwendung eines partiellen Pixel‑Laders. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Liefert das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen. Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [`Save`](../../aspose.psd/datastreamsupporter/save/)‑Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie als zweiten Parameter an die [`Save`](../../aspose.psd/image/save/)‑Methode. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ermittelt ein Bildpixel. Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann. Für effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ermittelt den Schrägwinkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den Schrägwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformation eines Bildes in seine Graustufen‑Darstellung |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Lädt Pixel im CMYK‑Format. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Lädt Pixel im CMYK‑Format. Diese Methode ist veraltet. Bitte verwenden Sie effektiver die [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/)‑Methode. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32‑Bit‑ARGB‑Pixel teilweise in Paketen. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise in Paketen. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Führt die Ebenen zusammen. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalisiert den Winkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den schiefen Scan zu korrigieren. Diese Methode verwendet die [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)‑ und [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑Methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den schiefen Scan zu korrigieren. Diese Methode verwendet die [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)‑ und [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑Methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändert die Größe des Bildes. Der Standard‑NearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändert die Größe des Bildes. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ändert die Größe des Bildes. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Skaliert die Breite proportional. Der Standard‑NearestNeighbourResample wird verwendet. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Skaliert die Breite proportional. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Skaliert die Breite proportional. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Dreht das Bild um die Mitte. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Dreht das Bild um die Mitte. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [Save](../../aspose.psd/image/save/)() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Speichert die Objektdaten in den angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Objektdaten am angegebenen Speicherort. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Speichert die Objektdaten am angegebenen Speicherort. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Speichert die Pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Speichert die Pixel. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) . |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Speichert die Pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Speichert die Rohdaten. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Setzt die Bildpalette. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Setzt die Auflösung für dieses `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konvertiert das Rasterbild in das Bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Die Standard-PSD-Version. |

## Beispiele

Der folgende Code demonstriert die Fähigkeit, das Bild um einen bestimmten Winkelwert zu drehen.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Gesamtes Bild drehen
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

// Ebene drehen
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
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


