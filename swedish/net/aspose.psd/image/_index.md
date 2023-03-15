---
title: Class Image
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Image klass. Bilden är basklassen för alla typer av bilder.
type: docs
weight: 4590
url: /sv/net/aspose.psd/image/
---
## Image class

Bilden är basklassen för alla typer av bilder.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller ställer in ett värde som anger om paletten för automatisk justering. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller ställer in ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Hämtar bildbitar per pixelantal. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Får bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [Container](../../aspose.psd/image/container/) { get; } | Får`Image` container. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets dataström. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Får värdet filformat |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller ställer in ett värde som anger om bilden har bakgrundsfärg. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Hämtar bildhöjden. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller ställer in avbrottsmonitorn. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Får ett värde som indikerar om objektets data är cachad för närvarande och ingen dataläsning krävs. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller ställer in färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Hämtar bildens bredd. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Skapar en ny bild med de angivna skapaalternativen. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Laddar en ny bild från den angivna strömmen. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Laddar en ny bild från den angivna filen. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Laddar en ny bild från den angivna strömmen. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Laddar en ny bild från den angivna filen. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachelagrar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från det underliggande[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas i det angivna filformatet som representeras av de godkända sparalternativen. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara till hjälp för att behålla bitdjupet och andra parametrar i originalbilden oförändrade. Om vi till exempel laddar en svartvit PNG-bild med 1 bit per pixel och sedan spara den med hjälp av [`Save`](../datastreamsupporter/save/) metod, kommer den utgående PNG-bilden med 8-bitar per pixel att produceras. För att undvika det och spara PNG-bild med 1-bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till[`Save`](./save/)metod som den andra parametern. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Ändrar storleken på bilden. StandardenLeftTopToLeftTopanvänds. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Ändrar storlek på bilden. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändrar storleken på höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Ändrar storleken på höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändrar storleken på bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Ändrar storleken på bredden proportionellt. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Roterar, vänder eller roterar och vänder bilden. |
| [Save](../../aspose.psd/image/save/#save)() | Sparar bilddata till den underliggande strömmen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Bestämmer om bilden kan laddas från den angivna strömmen. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Bestämmer om bilden kan laddas från den angivna sökvägen. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Bestämmer om bilden kan laddas från den angivna strömmen och eventuellt använda den angivna*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Bestämmer om bilden kan laddas från den angivna sökvägen och eventuellt med de angivna öppna alternativen. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Hämtar filformatet. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Hämtar filformatet. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Får rektangel som passar den aktuella bilden. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Får rektangel som passar den aktuella bilden. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Får en proportionell höjd. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Får en proportionell bredd. |

### Exempel

Det här exemplet skapar en ny bildfil på någon diskplats som specificeras av Source-egenskapen för PsdOptions-instansen. Flera egenskaper för PsdOptions-instansen ställs in innan den faktiska bilden skapas. Speciellt egenskapen Source, som refererar till den faktiska diskplatsen i det här fallet.

```csharp
[C#]

//Skapa en instans av PsdOptions och ställ in dess olika egenskaper
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Skapa en instans av FileCreateSource och tilldela den som källa för instansen av PsdOptions
//Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Skapa en instans av bild och initiera den med instans av PsdOptions genom att anropa metoden Skapa
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //gör lite bildbehandling

    // spara alla ändringar
    image.Save();
}
```

### Se även

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


