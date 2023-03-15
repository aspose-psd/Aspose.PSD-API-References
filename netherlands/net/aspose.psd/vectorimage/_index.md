---
title: Class VectorImage
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.VectorImage klas. De vectorafbeelding is de basisklasse voor alle soorten vectorafbeeldingen.
type: docs
weight: 5720
url: /nl/net/aspose.psd/vectorimage/
---
## VectorImage class

De vectorafbeelding is de basisklasse voor alle soorten vectorafbeeldingen.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Haalt of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Haalt of stelt een waarde in voor de achtergrondkleur. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Haalt het aantal beeldbits per pixel op. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Haalt de afbeeldingsgrenzen op. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Krijgt de[`Image`](../image/) container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Haalt de gegevensstroom van het object op. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Krijgt een waarde van bestandsformaat |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeelding een achtergrondkleur heeft. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Haalt de afbeeldingshoogte op. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Krijgt de hoogte van het object, in inches. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Haalt of stelt de interruptmonitor in. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Krijgt een waarde die aangeeft of de gegevens van het object momenteel in de cache zijn opgeslagen en dat er geen gegevens moeten worden gelezen. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| [Size](../../aspose.psd/image/size/) { get; } | Haalt de afbeeldingsgrootte op. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Krijgt de objectgrootte, in inches. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Haalt de beeldbreedte op. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Krijgt de objectbreedte, in inches. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cache de gegevens op en zorgt ervoor dat er geen aanvullende gegevens worden geladen vanaf de onderliggende gegevens[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bepaalt of de afbeelding kan worden opgeslagen in de opgegeven bestandsindeling die wordt weergegeven door de doorgegeven opslagopties. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Krijgt de standaardopties. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Krijgt de opties op basis van de originele bestandsinstellingen. Dit kan handig zijn om de bitdiepte en andere parameters van de originele afbeelding ongewijzigd te laten. Als we bijvoorbeeld een zwart-wit PNG-afbeelding laden met 1 bit per pixel en sla het op met the [`Save`](../datastreamsupporter/save/) methode, wordt de uitgevoerde PNG-afbeelding met 8-bits per pixel geproduceerd. Om dit te voorkomen en PNG-afbeelding met 1-bits per pixel op te slaan, gebruikt u deze methode om overeenkomstige opslagopties te krijgen en deze door te geven aan de[`Save`](../image/save/)methode als de tweede parameter. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Pas de grootte van de afbeelding aan. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Pas de grootte van de afbeelding aan. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Pas de hoogte proportioneel aan. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Pas de breedte proportioneel aan. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [Save](../../aspose.psd/image/save/)() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Slaat de gegevens van het object op in de opgegeven stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Stelt het afbeeldingspalet in. |

### Zie ook

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


