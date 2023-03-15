---
title: Class PsdLoadOptions
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions klass. Psd laddningsalternativ
type: docs
weight: 4770
url: /sv/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd laddningsalternativ

```csharp
public class PsdLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Hämtar eller ställer in om det ska sparas med den renderade bilden, med eller utan en varptransform. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Hämtar eller ställer in[`Image`](../../aspose.psd/image/) bakgrund[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Hämtar eller ställer in dataåterställningsläget. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Hämtar eller ställer in ett värde som anger om [ignorera alfakanal]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om PSD-textskiktets fasta bredd kommer att ignoreras när UpdateText-operationen körs. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om [lasteffektresurs] (som standard resurs inte laddas). När det här alternativet är inställt kommer endast effekter som stöds att renderas till den slutliga sammanslagna bilden. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Hämtar eller ställer in ett värde som anger om [använd skrivskyddat läge]. Detta är skrivskyddat läge som stöds för identisk kompatibilitet med Adobe Photoshop. När det här alternativet är inställt sparas inte alla ändringar som tillämpas för lager i den slutliga bilden. All data används från ImageData-sektionen, så den är identisk med Photoshop. Som standard är alla inlästa bilder inte identiska med Adobe Photoshop-kompatibla. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om [använd disk för laddningseffektresurs] (används som standard disk för att ladda effektresurs, men kan användas minne om det räcker genom att sätta detta värde till false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Hämtar eller ställer in ett värde som anger om ICC-profilkonvertering ska tillämpas. |

### Exempel

Följande exempel visar att dokumentkonverteringen fungerar korrekt och utan undantag.

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
* namnutrymme [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* hopsättning [Aspose.PSD](../../)


