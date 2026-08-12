---
title: "Klassen Image"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Image-klass. Bilden är basklassen för alla typer av bilder"
type: docs
weight: 5060
url: /sv/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

Bilden är basklassen för alla typer av bilder.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller anger ett värde som indikerar om paletten justeras automatiskt. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller anger ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Hämtar antalet bildbitar per pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Hämtar bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [Container](../../aspose.psd/image/container/) { get; } | Hämtar `Image`-behållaren. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets datastream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Hämtar ett värde för filformatet |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Hämtar bildens höjd. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller anger avbrottsmotorn. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Hämtar ett värde som indikerar om bildpaletten används. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Hämtar bildbredden. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Skapar en ny bild med de angivna skapalternativen. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Läser in en ny bild från den angivna strömmen. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Läser in en ny bild från den angivna filen. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Läser in en ny bild från den angivna strömmen. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Läser in en ny bild från den angivna filen. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på originalfilens inställningar. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi läser in en svart-vit PNG-bild med 1 bit per pixel och sedan sparar den med metoden [`Save`](../datastreamsupporter/save/), kommer en PNG-bild med 8 bitar per pixel att skapas. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till metoden [`Save`](./save/) som den andra parametern. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Ändrar bildens storlek. Standardvärdet NearestNeighbourResample används. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Ändrar bildens storlek. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Ändrar bildens storlek. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ändrar höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Ändrar bredden proportionellt. Standardvärdet NearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändrar bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Ändrar bredden proportionellt. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Rotera, vänd eller rotera och vänd bilden. |
| [Save](../../aspose.psd/image/save/#save)() | Sparar bilddata till den underliggande strömmen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna *loadOptions*. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Hämtar filformatet. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Hämtar filformatet. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Hämtar rektangeln som passar den aktuella bilden. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Hämtar rektangeln som passar den aktuella bilden. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Hämtar en proportionell höjd. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Hämtar en proportionell bredd. |

## Exempel

Detta exempel skapar en ny bildfil på en viss diskplats enligt Source‑egenskapen i PsdOptions‑instansen. Flera egenskaper för PsdOptions‑instansen sätts innan den faktiska bilden skapas. Speciellt Source‑egenskapen, som i detta fall refererar till den faktiska diskplatsen.

```csharp
[C#]

//Skapa en instans av PsdOptions och ange dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av FileCreateSource och tilldela den som Source för instansen av PsdOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Skapa en instans av Image och initiera den med en instans av PsdOptions genom att anropa Create‑metoden
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //utför någon bildbehandling

    // spara alla ändringar
    image.Save();
}
```

### Se även

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


