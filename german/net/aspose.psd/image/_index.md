---
title: Image
second_title: Aspose.PSD für .NET-API-Referenz
description: Das Bild ist die Basisklasse für alle Arten von Bildern.
type: docs
weight: 4520
url: /de/net/aspose.psd/image/
---
## Image class

Das Bild ist die Basisklasse für alle Arten von Bildern.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.psd/image/container) { get; } | Ruft die ab[`Image`](../image) Container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| abstract [Height](../../aspose.psd/image/height) { get; } | Ruft die Bildhöhe ab. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached) { get; } | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [Size](../../aspose.psd/image/size) { get; } | Ruft die Bildgröße ab. |
| abstract [Width](../../aspose.psd/image/width) { get; } | Ruft die Bildbreite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.psd/image/create)(ImageOptionsBase, int, int) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| static [Load](../../aspose.psd/image/load#load)(Stream) | Lädt ein neues Bild aus dem angegebenen Stream. |
| static [Load](../../aspose.psd/image/load#load_2)(string) | Lädt ein neues Bild aus der angegebenen Datei. |
| static [Load](../../aspose.psd/image/load#load_1)(Stream, LoadOptions) | Lädt ein neues Bild aus dem angegebenen Stream. |
| static [Load](../../aspose.psd/image/load#load_3)(string, LoadOptions) | Lädt ein neues Bild aus der angegebenen Datei. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata)() | Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](./save)Methode als zweiten Parameter. |
| [Resize](../../aspose.psd/image/resize#resize)(int, int) | Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet. |
| abstract [Resize](../../aspose.psd/image/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| abstract [Resize](../../aspose.psd/image/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally)(int) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally)(int) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.psd/image/save#save)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| [Save](../../aspose.psd/image/save#save_2)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.psd/image/save#save_5)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.psd/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| abstract [SetPalette](../../aspose.psd/image/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |
| static [CanLoad](../../aspose.psd/image/canload#canload)(Stream) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann. |
| static [CanLoad](../../aspose.psd/image/canload#canload_2)(string) | Legt fest, ob das Bild aus dem angegebenen Dateipfad geladen werden kann. |
| static [CanLoad](../../aspose.psd/image/canload#canload_1)(Stream, LoadOptions) | Legt fest, ob das Bild aus dem angegebenen Stream geladen werden kann und optional den angegebenen verwendet*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload#canload_3)(string, LoadOptions) | Legt fest, ob das Bild aus dem angegebenen Dateipfad und optional unter Verwendung der angegebenen Öffnungsoptionen geladen werden kann. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat)(Stream) | Ruft das Dateiformat ab. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat_1)(string) | Ruft das Dateiformat ab. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Ruft ein Rechteck ab, das zum aktuellen Bild passt. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Ruft ein Rechteck ab, das zum aktuellen Bild passt. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight)(int, int, int) | Ruft eine proportionale Höhe ab. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth)(int, int, int) | Ruft eine proportionale Breite ab. |

### Beispiele

In diesem Beispiel wird eine neue Bilddatei an einem Speicherort auf dem Datenträger erstellt, wie durch die Source-Eigenschaft der PsdOptions-Instanz angegeben. Mehrere Eigenschaften für die PsdOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von PsdOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von PsdOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create-Methode aufrufen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
