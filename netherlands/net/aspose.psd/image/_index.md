---
title: Class Image
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Image klas. De afbeelding is de basisklasse voor alle soorten afbeeldingen.
type: docs
weight: 4590
url: /nl/net/aspose.psd/image/
---
## Image class

De afbeelding is de basisklasse voor alle soorten afbeeldingen.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Haalt of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Haalt of stelt een waarde in voor de achtergrondkleur. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Haalt het aantal beeldbits per pixel op. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Haalt de afbeeldingsgrenzen op. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Krijgt de`Image` container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Haalt de gegevensstroom van het object op. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Krijgt een waarde van bestandsformaat |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de afbeelding een achtergrondkleur heeft. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Haalt de afbeeldingshoogte op. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Haalt of stelt de interruptmonitor in. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Krijgt een waarde die aangeeft of de gegevens van het object momenteel in de cache zijn opgeslagen en dat er geen gegevens moeten worden gelezen. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Haalt of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| [Size](../../aspose.psd/image/size/) { get; } | Haalt de afbeeldingsgrootte op. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Haalt de beeldbreedte op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Maakt een nieuwe afbeelding met de opgegeven aanmaakopties. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Laadt een nieuwe afbeelding uit het opgegeven bestand. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Laadt een nieuwe afbeelding van de opgegeven stream. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Laadt een nieuwe afbeelding uit het opgegeven bestand. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cache de gegevens op en zorgt ervoor dat er geen aanvullende gegevens worden geladen vanaf de onderliggende gegevens[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bepaalt of de afbeelding kan worden opgeslagen in de opgegeven bestandsindeling die wordt weergegeven door de doorgegeven opslagopties. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Krijgt de standaardopties. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Krijgt de opties op basis van de originele bestandsinstellingen. Dit kan handig zijn om de bitdiepte en andere parameters van de originele afbeelding ongewijzigd te laten. Als we bijvoorbeeld een zwart-wit PNG-afbeelding laden met 1 bit per pixel en sla het op met the [`Save`](../datastreamsupporter/save/) methode, wordt de uitgevoerde PNG-afbeelding met 8-bits per pixel geproduceerd. Om dit te voorkomen en PNG-afbeelding met 1-bits per pixel op te slaan, gebruikt u deze methode om overeenkomstige opslagopties te krijgen en deze door te geven aan de[`Save`](./save/)methode als de tweede parameter. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Pas de grootte van de afbeelding aan. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Pas de grootte van de afbeelding aan. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Pas de hoogte proportioneel aan. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Pas de hoogte proportioneel aan. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Pas de breedte proportioneel aan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Pas de breedte proportioneel aan. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| [Save](../../aspose.psd/image/save/#save)() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Slaat de gegevens van het object op in de opgegeven stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Slaat de objectgegevens op naar de opgegeven bestandslocatie. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Slaat de afbeeldingsgegevens op in de opgegeven stream in de opgegeven bestandsindeling volgens de opslagopties. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Slaat de objectgegevens op naar de opgegeven bestandslocatie in de opgegeven bestandsindeling volgens de opslagopties. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Stelt het afbeeldingspalet in. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Bepaalt of afbeelding kan worden geladen uit de opgegeven stream. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Bepaalt of afbeelding kan worden geladen vanuit het opgegeven bestandspad. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Bepaalt of de afbeelding kan worden geladen vanuit de opgegeven stream en optioneel met behulp van de opgegeven*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Bepaalt of afbeelding kan worden geladen vanuit het opgegeven bestandspad en optioneel met behulp van de opgegeven open-opties. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Haalt het bestandsformaat op. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Haalt het bestandsformaat op. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Krijgt een rechthoek die past bij de huidige afbeelding. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Krijgt een rechthoek die past bij de huidige afbeelding. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Krijgt een proportionele hoogte. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Krijgt een proportionele breedte. |

### Voorbeelden

In dit voorbeeld wordt een nieuw afbeeldingsbestand gemaakt op een bepaalde schijflocatie, zoals gespecificeerd door de eigenschap Source van de instantie PsdOptions. Verschillende eigenschappen voor de PsdOptions-instantie worden ingesteld voordat de eigenlijke afbeelding wordt gemaakt. Vooral de eigenschap Source, die in dit geval verwijst naar de daadwerkelijke schijflocatie.

```csharp
[C#]

//Maak een instantie van PsdOptions en stel de verschillende eigenschappen in
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Maak een instantie van FileCreateSource en wijs deze toe als bron voor de instantie van PsdOptions
//De tweede Booleaanse parameter bepaalt of het aan te maken bestand IsTemporal is of niet
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Maak een exemplaar van Image en initialiseer het met een exemplaar van PsdOptions door de Create-methode aan te roepen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // doe wat beeldverwerking

    // sla alle veranderingen op
    image.Save();
}
```

### Zie ook

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


