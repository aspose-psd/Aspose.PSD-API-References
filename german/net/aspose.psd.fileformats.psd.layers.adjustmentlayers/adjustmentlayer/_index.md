---
title: "Klasse AdjustmentLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.AdjustmentLayer Klasse. Anpassungsebene. Zum Beispiel Helligkeit/Kontrast."
type: docs
weight: 1700
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/
---
{{< psd/tize >}}
## AdjustmentLayer class

Anpassungsebene. Zum Beispiel Helligkeit/Kontrast

```csharp
public abstract class AdjustmentLayer : Layer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Liest die Bit‑pro‑Pixel‑Anzahl des Bildes. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Liest oder setzt das Blending des beschnittenen Elements. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Liest die Blending‑Optionen. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Liest oder setzt den Schlüssel des Mischmodus. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Liest die Signatur des Mischmodus. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Liest oder setzt die Position der unteren Ebene. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Liest die Bildgrenzen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Liest oder setzt die Kanalinformationen. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Liest die Anzahl der Kanäle der Ebene. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Liest oder setzt das Ebenen‑Clipping. 0 = Basis, 1 = Nicht‑Basis. |
| [Container](../../aspose.psd/image/container/) { get; } | Liest den [`Image`](../../aspose.psd/image/)‑Container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Liest den Datenstrom des Objekts. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Liest oder setzt den Anzeigenamen der Ebene. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Liefert die zusätzliche Informationslänge der Ebene in Bytes. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Liefert einen Wert des Dateiformats |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Liefert oder setzt den Ebenen‑Füller. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Liefert oder setzt die Füll‑Deckkraft. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Liefert oder setzt die Ebenen‑Flags. Bit 0 = Transparenz geschützt; Bit 1 = sichtbar; Bit 2 = veraltet; Bit 3 = 1 für Photoshop 5.0 und neuer, gibt an, ob Bit 4 nützliche Informationen enthält; Bit 4 = Pixeldaten, die für das Erscheinungsbild des Dokuments irrelevant sind. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Liefert einen Wert, der angibt, ob diese Instanz Alpha enthält. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Liefert einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Liefert die Bildhöhe. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Liefert oder setzt die horizontale Auflösung in Pixeln pro Zoll dieses [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Liefert die Deckkraft dieses Bildes. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Liefert oder setzt den Unterbrechungsmonitor. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Liefert einen Wert, der angibt, ob Bilddaten derzeit im Cache sind. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Liefert einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Liefert einen Wert, der angibt, ob diese Instanz in einer Gruppe sichtbar ist (Wenn die Ebene nicht in einer Gruppe ist, bedeutet das die Stammgruppe). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Liefert oder setzt die Daten der Ebenen‑Blending‑Bereiche. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Liefert oder setzt das Erstellungsdatum und die -zeit der Ebene. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Liefert oder setzt die Ebenensperre. Hinweis, dass wenn das Flag LayerFlags.TransparencyProtected gesetzt ist, es durch das Ebenensperre‑Flag überschrieben wird. Um das Flag LayerFlags.TransparencyProtected zurückzugeben, muss die Ebenenoption layer.Flags &#x7C;= LayerFlags.TransparencyProtected angewendet werden. |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Liefert oder setzt die Ebenenmaskendaten. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Liefert die Ebenenoptionen. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Liefert oder setzt die linke Position der Ebene. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Liefert die gesamte Ebenenlänge in Bytes. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Liefert oder setzt den Ebenennamen. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Liefert oder setzt die Ebenendeckkraft. 0 = transparent, 255 = undurchsichtig. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvervielfacht werden müssen. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Liest oder setzt den benutzerdefinierten Farbkonverter |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Liest das Rohdatenformat. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Liest die aktuellen Rohdaten-Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Liest oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Liest die Rohzeilengröße in Bytes. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Liest oder setzt die Ebenenressourcen. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Liest oder setzt die rechte Ebenenposition. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Liest oder setzt die dekorative Blattfarb-Hervorhebung in der Ebenenliste |
| [Size](../../aspose.psd/image/size/) { get; } | Liest die Bildgröße. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Liest oder setzt die obere Ebenenposition. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Liest die transparente Bildfarbe. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses [`RasterImage`](../../aspose.psd/rasterimage/). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Liest die Bildbreite. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Liest oder setzt die XMP-Metadaten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Fügt die Maske zur aktuellen Ebene hinzu. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Anpassung der Helligkeit für das Bild. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Bildkontrastierung |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-Korrektur eines Bildes. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Wendet die Ebenenmaske auf die Ebene an und löscht dann die Maske. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisierung eines Bildes mit Otsu‑Schwellenwertbestimmung |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) durchgeführt werden. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Zuschneiden des Bildes. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Führt Dithering am aktuellen Bild aus. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Führt Dithering am aktuellen Bild aus. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Zeichnet das Bild auf die Ebene. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Liefert ein 32‑Bit‑ARGB‑Pixel eines Bildes. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Liefert die Standardoptionen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Liefert das Standard‑Pixel‑Array unter Verwendung eines partiellen Pixel‑Laders. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Liefert das Standard‑Rohdaten‑Array. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Liefert das Standard‑Rohdaten‑Array unter Verwendung eines partiellen Pixel‑Laders. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Liefert das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen. Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [`Save`](../../aspose.psd/datastreamsupporter/save/)‑Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1‑Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie als zweiten Parameter an die [`Save`](../../aspose.psd/image/save/)‑Methode. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ermittelt ein Bildpixel. Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann. Für effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ermittelt den Schrägwinkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den Schrägwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformation eines Bildes in seine Graustufen‑Darstellung |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Lädt Pixel im CMYK‑Format. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Lädt Pixel im CMYK‑Format. Diese Methode ist veraltet. Bitte verwenden Sie effektiver die [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/)‑Methode. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32‑Bit‑ARGB‑Pixel teilweise in Paketen. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise in Paketen. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | Führt die Ebene mit der angegebenen Ebene zusammen |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalisiert den Winkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den schiefen Scan zu korrigieren. Diese Methode verwendet die [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)‑ und [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑Methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den schiefen Scan zu korrigieren. Diese Methode verwendet die [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/)‑ und [`Rotate`](../../aspose.psd/rasterimage/rotate/)‑Methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändert die Größe des Bildes. Der Standard‑NearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Ändert die Größe des Bildes. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Ändert die Größe des Bildes. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Skaliert die Breite proportional. Der Standard‑NearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Skaliert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Skaliert die Breite proportional. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Dreht das Bild um die Mitte. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Dreht das Bild um die Mitte. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [Save](../../aspose.psd/image/save/)() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Speichert die Objektdaten in den angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Objektdaten am angegebenen Speicherort. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Speichert die Objektdaten am angegebenen Speicherort. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Speichert die Pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Speichert die Pixel. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) . |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Speichert die Pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Speichert die Rohdaten. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Setzt die Bildpalette. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Setzt die Auflösung für dieses [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Erstellt eine flache Kopie der aktuellen Ebene. Bitte [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) für eine Erklärung. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konvertiert das Rasterbild in das Bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |

### Siehe auch

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


