---
title: Class PsdLoadOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions klas. PsdLadeoptionen
type: docs
weight: 4770
url: /de/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd-Ladeoptionen

```csharp
public class PsdLoadOptions : LoadOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Ruft ab oder legt fest, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Warp-Transformation. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Ruft ab oder setzt die[`Image`](../../aspose.psd/image/) Hintergrund[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Ruft den Datenwiederherstellungsmodus ab oder legt ihn fest. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Alphakanal ignorieren]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die feste Breite der PSD-Textebene bei der Ausführung des UpdateText-Vorgangs ignoriert wird. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Last wirkt sich auf Ressource] aus (standardmäßig wird die Ressource nicht geladen). Wenn diese Option aktiviert ist, werden nur unterstützte Effekte in das endgültig zusammengeführte Bild gerendert. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Nur-Lese-Modus verwenden]. Dies ist ein schreibgeschützter Modus, der für identische Kompatibilität mit Adobe Photoshop unterstützt wird. Wenn diese Option aktiviert ist, werden alle auf Ebenen angewendeten Änderungen nicht im endgültigen Bild gespeichert. Alle Daten werden aus dem Abschnitt ImageData verwendet, sind also identisch mit Photoshop. Standardmäßig sind alle geladenen Bilder nicht identisch mit Adobe Photoshop kompatibel. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Datenträger zum Laden der Effektressource verwenden] (standardmäßig wird der Datenträger zum Laden der Effektressource verwendet, kann aber als Speicher verwendet werden, wenn er ausreicht, indem dieser Wert auf „false“ gesetzt wird). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |

### Beispiele

Das folgende Beispiel zeigt, dass der Dokumentkonvertierungsfortschritt korrekt und ohne Ausnahme funktioniert.

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

### Siehe auch

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namensraum [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* Montage [Aspose.PSD](../../)


