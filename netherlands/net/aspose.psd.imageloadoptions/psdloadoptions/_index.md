---
title: Class PsdLoadOptions
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions klas. Psdlaadopties
type: docs
weight: 4770
url: /nl/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd-laadopties

```csharp
public class PsdLoadOptions : LoadOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Krijgt of stelt in of moet worden opgeslagen met de gerenderde afbeelding, met of zonder een warp-transformatie. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Haalt de hint voor de buffergrootte op of stelt deze in, de maximale toegestane grootte voor alle interne buffers. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Haalt of stelt de[`Image`](../../aspose.psd/image/) achtergrond[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Krijgt of stelt de gegevensherstelmodus in. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [alfakanaal negeren]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of de vaste breedte van de PSD-tekstlaag wordt genegeerd bij de uitvoering van de UpdateText-bewerking. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [bron effecten laden] (bron wordt standaard niet geladen). Als deze optie is ingesteld, worden alleen ondersteunde effecten weergegeven in de uiteindelijke samengevoegde afbeelding. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Haalt de voortgangsgebeurtenishandler op of stelt deze in. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [alleen-lezenmodus gebruiken]. Dit is alleen-lezen modus, ondersteund voor identieke compatibiliteit met Adobe Photoshop. Wanneer deze optie is ingesteld, worden alle aangebrachte wijzigingen voor lagen niet opgeslagen in de uiteindelijke afbeelding. Alle gegevens worden gebruikt uit de ImageData-sectie, dus het is identiek aan Photoshop. Standaard zijn alle geladen afbeeldingen niet identiek aan Adobe Photoshop-compatibel. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [schijf gebruiken voor het laden van effectenresource] (standaard gebruikte schijf om effectenresource te laden, maar kan geheugen worden gebruikt als het genoeg is door deze waarde in te stellen op false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of ICC-profielconversie moet worden toegepast. |

### Voorbeelden

Het volgende voorbeeld laat zien dat de voortgang van de documentconversie correct en zonder uitzondering werkt.

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

### Zie ook

* class [LoadOptions](../../aspose.psd/loadoptions/)
* naamruimte [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* montage [Aspose.PSD](../../)


