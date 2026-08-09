---
title: "Klasse VectorImage"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.VectorImage‑Klasse. Das Vektor‑Bild ist die Basisklasse für alle Arten von Vektor‑Bildern"
type: docs
weight: 6220
url: /de/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

Das Vektorbild ist die Basisklasse für alle Arten von Vektorbildern.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Liefert die Bildhöhe. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Ermittelt die Objekt-Höhe in Zoll. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Liefert oder setzt den Unterbrechungsmonitor. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit im Cache sind und kein Datenlesen erforderlich ist. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [Size](../../aspose.psd/image/size/) { get; } | Liest die Bildgröße. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Ermittelt die Objektgröße in Zoll. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Liest die Bildbreite. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Ermittelt die Objektbreite in Zoll. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cached die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) durchgeführt werden. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Liefert die Standardoptionen. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und es dann mit der [`Save`](../datastreamsupporter/save/) Methode speichern, wird ein PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie als zweiten Parameter an die [`Save`](../image/save/) Methode. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändert die Größe des Bildes. Der Standard‑NearestNeighbourResample wird verwendet. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Ändert die Größe des Bildes. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Ändert die Größe des Bildes. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Skaliert die Breite proportional. Der Standard‑NearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Skaliert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Skaliert die Breite proportional. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [Save](../../aspose.psd/image/save/)() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Speichert die Objektdaten in den angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Objektdaten am angegebenen Speicherort. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Speichert die Objektdaten am angegebenen Speicherort. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Setzt die Bildpalette. |

### Siehe auch

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


