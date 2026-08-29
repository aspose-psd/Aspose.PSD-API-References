---
title: "Klasse RasterImage"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.RasterImage Klasse. Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt"
type: docs
weight: 5820
url: /de/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

Stellt ein Rasterbild dar, das Rastergrafik-Operationen unterstützt.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Liest die Bit‑pro‑Pixel‑Anzahl des Bildes. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Liest die Bildgrenzen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [Container](../../aspose.psd/image/container/) { get; } | Ruft den [`Image`](../image/) Container ab. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Liest den Datenstrom des Objekts. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Liefert einen Wert des Dateiformats |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Liefert einen Wert, der angibt, ob diese Instanz Alpha enthält. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Liefert einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Liefert die Bildhöhe. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Liest oder setzt die horizontale Auflösung in Pixel pro Zoll dieses `RasterImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Liefert die Deckkraft dieses Bildes. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Liefert oder setzt den Unterbrechungsmonitor. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit im Cache sind und kein Datenlesen erforderlich ist. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Liefert einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvervielfacht werden müssen. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Liest oder setzt den benutzerdefinierten Farbkonverter |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Liest das Rohdatenformat. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Liest die aktuellen Rohdaten-Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Liest oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Liest die Rohzeilengröße in Bytes. |
| [Size](../../aspose.psd/image/size/) { get; } | Liest die Bildgröße. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Liest die transparente Bildfarbe. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses `RasterImage`. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Liest die Bildbreite. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Liest oder setzt die XMP-Metadaten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Anpassung der Helligkeit für das Bild. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Bildkontrastierung |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-Korrektur eines Bildes. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild‑Schwellenwertbestimmung |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Binarisierung eines Bildes mit Otsu‑Schwellenwertbestimmung |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cached die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) durchgeführt werden. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Schneidet das angegebene Rechteck zu. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Führt Dithering am aktuellen Bild aus. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Führt Dithering am aktuellen Bild aus. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Liefert ein 32‑Bit‑ARGB‑Pixel eines Bildes. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Liefert das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Liefert die Standardoptionen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Liefert das Standard‑Pixel‑Array unter Verwendung eines partiellen Pixel‑Laders. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Liefert das Standard‑Rohdaten‑Array. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Liefert das Standard‑Rohdaten‑Array unter Verwendung eines partiellen Pixel‑Laders. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Liefert das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und es dann mit der [`Save`](../datastreamsupporter/save/) Methode speichern, wird ein PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie als zweiten Parameter an die [`Save`](../image/save/) Methode. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Ermittelt ein Bildpixel. Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann. Für effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Ermittelt den Schrägwinkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um den Schrägwinkel beim Scannen zu bestimmen. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Transformation eines Bildes in seine Graustufen‑Darstellung |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Lädt Pixel im CMYK‑Format. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Lädt Pixel im CMYK-Format. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`LoadCmyk32Pixels`](./loadcmyk32pixels/) Methode. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32‑Bit‑ARGB‑Pixel teilweise in Paketen. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise in Paketen. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren. Diese Methode verwendet die [`GetSkewAngle`](./getskewangle/) und [`Rotate`](./rotate/) Methoden. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um die schiefe Aufnahme zu korrigieren. Diese Methode verwendet die [`GetSkewAngle`](./getskewangle/) und [`Rotate`](./rotate/) Methoden. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändert die Größe des Bildes. Der Standard‑NearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Skaliert das Bild mit erweiterten Optionen. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Ändert die Größe des Bildes. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Skaliert die Breite proportional. Der Standard‑NearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Skaliert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Skaliert die Breite proportional. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Dreht das Bild um die Mitte. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Dreht das Bild um die Mitte. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [Save](../../aspose.psd/image/save/)() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Speichert die Objektdaten in den angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Objektdaten am angegebenen Speicherort. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Speichert die Objektdaten am angegebenen Speicherort. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Speichert die Pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Speichert die Pixel. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`SaveCmyk32Pixels`](./savecmyk32pixels/) Methode. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Speichert die Pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Speichert die Rohdaten. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Setzt die Bildpalette. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Legt die Auflösung für dieses `RasterImage` fest. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konvertiert das Rasterbild in das Bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |

## Beispiele

Dieses Beispiel zeigt, wie Pixelinformationen in einem Array vom Typ Color geladen, das Array manipuliert und zurück zum Bild gesetzt werden. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im PSD-Format) mithilfe eines MemoryStream-Objekts.

```csharp
[C#]

//Erstelle eine Instanz von MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstelle eine Instanz von PsdOptions und setze deren verschiedene Eigenschaften, einschließlich der Source-Eigenschaft
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Erstelle eine Instanz von Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Hole die Pixel des Bildes, indem du den Bereich als Bildgrenze angibst
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Durchlaufe das Array und setze die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Setze die Farbe des indizierten Pixels auf Gelb
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Setze die Farbe des indizierten Pixels auf Blau
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Wende die Pixeländerungen auf das Bild an
        image.SavePixels(image.Bounds, pixels);

        // Speichere alle Änderungen.
        image.Save();
    }

    //Schreibe MemoryStream in eine Datei
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Siehe auch

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


