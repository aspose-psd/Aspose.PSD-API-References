---
title: "Klasse Image"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Image‑Klasse. Das Bild ist die Basisklasse für alle Bildtypen."
type: docs
weight: 5060
url: /de/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

Das Bild ist die Basisklasse für alle Bildtypen.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Liest die Bit‑pro‑Pixel‑Anzahl des Bildes. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Liest die Bildgrenzen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [Container](../../aspose.psd/image/container/) { get; } | Liefert den `Image`‑Container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Liest den Datenstrom des Objekts. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Liefert einen Wert des Dateiformats |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Liefert die Bildhöhe. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Liefert oder setzt den Unterbrechungsmonitor. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit im Cache sind und kein Datenlesen erforderlich ist. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [Size](../../aspose.psd/image/size/) { get; } | Liest die Bildgröße. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Liest die Bildbreite. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Lädt ein neues Bild aus dem angegebenen Stream. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Lädt ein neues Bild aus der angegebenen Datei. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Lädt ein neues Bild aus dem angegebenen Stream. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Lädt ein neues Bild aus der angegebenen Datei. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cached die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) durchgeführt werden. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Liefert die Standardoptionen. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Holt die Optionen basierend auf den Originaldateieinstellungen. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [`Save`](../datastreamsupporter/save/)‑Methode speichern, wird ein Ausgabepng‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und übergeben Sie sie der [`Save`](./save/)‑Methode als zweiten Parameter. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Ändert die Größe des Bildes. Der Standard‑NearestNeighbourResample wird verwendet. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Ändert die Größe des Bildes. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Ändert die Größe des Bildes. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Skaliert die Breite proportional. Der Standard‑NearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Skaliert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Skaliert die Breite proportional. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| [Save](../../aspose.psd/image/save/#save)() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Speichert die Objektdaten in den angegebenen Stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Speichert die Objektdaten am angegebenen Speicherort. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Speichert die Objektdaten am angegebenen Speicherort. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Speichert die Objektdaten am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Setzt die Bildpalette. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Bestimmt, ob das Bild aus dem angegebenen Dateipfad geladen werden kann. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann und optional die angegebenen *loadOptions* verwendet. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Bestimmt, ob das Bild aus dem angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Liefert das Dateiformat. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Liefert das Dateiformat. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Liefert das Rechteck, das zum aktuellen Bild passt. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Liefert eine proportionale Höhe. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Liefert eine proportionale Breite. |

## Beispiele

Dieses Beispiel erstellt eine neue Bilddatei an einem Speicherort, der durch die Source‑Eigenschaft der PsdOptions‑Instanz angegeben ist. Mehrere Eigenschaften der PsdOptions‑Instanz werden gesetzt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source‑Eigenschaft, die in diesem Fall auf den tatsächlichen Speicherort verweist.

```csharp
[C#]

//Erstellen Sie eine Instanz von PsdOptions und setzen Sie deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von PsdOptions zu.
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create‑Methode aufrufen.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


