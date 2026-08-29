---
title: "Klass PsdLoadOptions"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions class. Psd‑läsalternativ"
type: docs
weight: 5250
url: /sv/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

PSD-inläsningsalternativ

```csharp
public class PsdLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Hämtar eller anger om ursprungliga lagerpixlar ska bevaras under rendering om lagret inte har ändrats. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Hämtar eller anger om man ska spara med den renderade bilden, med eller utan en warp‑transformering. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Hämtar eller anger en hint för buffertstorleken som definierar maximal tillåten storlek för alla interna buffertar. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Hämtar eller anger bakgrunds[`Image`](../../aspose.psd/image/) [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Hämtar eller anger dataräddningsläget. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Hämtar eller anger ett värde som indikerar om [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Hämtar eller anger ett värde som indikerar om PSD‑textlagrets fasta bredd ska ignoreras vid körning av UpdateText‑operationen. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Hämtar eller anger ett värde som indikerar om [load effects resource] (standard är att resursen inte laddas). När detta alternativ är satt kommer endast stödjade effekter att renderas till den slutliga sammanslagna bilden. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Hämtar eller anger händelsehanteraren för framsteg. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Hämtar eller anger ett värde som indikerar om [use read only mode]. Detta är skrivskyddat läge, stödjt för exakt kompatibilitet med Adobe Photoshop. När detta alternativ är satt sparas inga ändringar som gjorts på lager i den slutliga bilden. All data hämtas från ImageData‑sektionen, så det är identiskt med Photoshop. Som standard är inte alla inlästa bilder identiska med Adobe Photoshop‑kompatibla. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Hämtar eller anger det skrivskyddade läget som används när en PSD‑bild laddas. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Hämtar eller anger ett värde som indikerar om [use disk for load effects resource] (standard är att använda disk för att ladda effektresursen, men minne kan användas om det är tillräckligt genom att sätta detta värde till false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Hämtar eller anger ett värde som indikerar om ICC‑profilkonvertering ska tillämpas. |

## Exempel

Följande exempel visar att dokumentkonverteringsframsteg fungerar korrekt och utan undantag.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### Se även

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


