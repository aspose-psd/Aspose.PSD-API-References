---
title: "Klass RasterImage"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.RasterImage-klass. Representerar en rasterbild som stöder rastergrafikoperationer"
type: docs
weight: 5820
url: /sv/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

Representerar en rasterbild som stöder rastergrafikoperationer.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Hämtar eller anger ett värde som indikerar om paletten justeras automatiskt. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Hämtar eller anger ett värde för bakgrundsfärgen. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Hämtar antalet bildbitar per pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Hämtar bildens gränser. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [Container](../../aspose.psd/image/container/) { get; } | Hämtar [`Image`](../image/) behållaren. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Hämtar objektets datastream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Hämtar ett värde för filformatet |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Hämtar ett värde som indikerar om detta objekt har alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Hämtar ett värde som indikerar om bilden har transparent färg. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Hämtar bildens höjd. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna `RasterImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Hämtar opaciteten för denna bild. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Hämtar eller anger avbrottsmotorn. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Hämtar ett värde som indikerar om inläsning av rådata är tillgänglig. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Hämtar eller anger den anpassade färgkonverteraren |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Hämtar rådataformatet. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Hämtar eller anger den indexerade färgkonverteraren |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Hämtar den råa radstorleken i byte. |
| [Size](../../aspose.psd/image/size/) { get; } | Hämtar bildstorleken. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Hämtar bildens transparenta färg. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Hämtar ett värde som indikerar om bildpaletten används. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna `RasterImage`. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Hämtar bildbredden. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Hämtar eller anger XMP-metadata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Justering av bildens ljusstyrka. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Bildkontrast |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Gamma-korrigering av en bild. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-korrigering av en bild. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Binarisering av en bild med fördefinierad tröskel |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Binarisering av en bild med Otsu-tröskelvärde |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de överförda sparalternativen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Beskär den angivna rektangeln. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Beskär bild med förskjutningar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Utför dithering på den aktuella bilden. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Utför dithering på den aktuella bilden. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtrerar den angivna rektangeln. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Hämtar en bildpixel i 32-bitars ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Hämtar standardalternativen. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Hämtar standardarrayen för rådata. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Hämtar datum och tid då resursbilden senast ändrades. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Hämtar alternativen baserat på de ursprungliga filinställningarna. Detta kan vara användbart för att behålla bitdjup och andra parametrar för den ursprungliga bilden oförändrade. Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av [`Save`](../datastreamsupporter/save/) metoden, kommer en PNG-bild med 8 bitar per pixel att produceras. För att undvika detta och spara PNG-bilden med 1 bit per pixel, använd den här metoden för att få motsvarande sparalternativ och skicka dem till [`Save`](../image/save/) metoden som den andra parametern. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Hämtar en bildpixel. Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem. För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Hämtar snedvinkeln. Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Transformation av en bild till dess gråskalerepresentation |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Laddar 32-bitars ARGB‑pixlar. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Laddar 64-bitars ARGB‑pixlar. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Laddar pixlar i CMYK-format. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Laddar pixlar i CMYK-format. Denna metod är föråldrad. Använd den mer effektiva [`LoadCmyk32Pixels`](./loadcmyk32pixels/) metoden. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Laddar 32-bitars ARGB‑pixlar delvis i paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Laddar pixlar delvis i paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Laddar pixlar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Laddar rådata. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](./getskewangle/) och [`Rotate`](./rotate/) metoderna. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning. Metoden använder [`GetSkewAngle`](./getskewangle/) och [`Rotate`](./rotate/) metoderna. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ändrar bildens storlek. Standardvärdet NearestNeighbourResample används. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Ändrar storlek på bilden med utökade alternativ. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Ändrar bildens storlek. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ändrar höjden proportionellt. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ändrar höjden proportionellt. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ändrar bredden proportionellt. Standardvärdet NearestNeighbourResample används. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ändrar bredden proportionellt. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ändrar bredden proportionellt. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Rotera bilden kring centrum. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Rotera bilden kring centrum. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Rotera, vänd eller rotera och vänd bilden. |
| [Save](../../aspose.psd/image/save/)() | Sparar bilddata till den underliggande strömmen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Sparar objektets data till den angivna strömmen. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Sparar objektets data till den angivna filplatsen. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Sparar objektets data till den angivna filplatsen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativen. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativen. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Sparar de 32-bitars ARGB-pixlarna. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Sparar pixlarna. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Sparar pixlarna. Denna metod är föråldrad. Använd den mer effektiva [`SaveCmyk32Pixels`](./savecmyk32pixels/) metoden. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Sparar pixlarna. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Sparar rådata. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ställer in bildpaletten. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ställer in en bildpixel för den angivna positionen. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Anger upplösningen för denna `RasterImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Konverterar rasterbild till bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |

## Exempel

Detta exempel visar hur man laddar pixelinformation i en array av typen Color, manipulerar arrayen och sätter tillbaka den i bilden. För att utföra dessa operationer skapar detta exempel en ny bildfil (i PSD-format) med hjälp av ett MemoryStream‑objekt.

```csharp
[C#]

//Skapa en instans av MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Skapa en instans av PsdOptions och ange dess olika egenskaper inklusive Source‑egenskapen
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Skapa en instans av Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Hämta bildens pixlar genom att specificera området som bildens gräns
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loopa över arrayen och sätter färg på alternativt indexerad pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Sätt färgen på den indexerade pixeln till gul
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Sätt färgen på den indexerade pixeln till blå
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Tillämpa pixeländringarna på bilden
        image.SavePixels(image.Bounds, pixels);

        // spara alla ändringar.
        image.Save();
    }

    //Skriv MemoryStream till fil
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Se även

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


