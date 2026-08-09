---
title: "Klasse PsdLoadOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions class. Psd-Ladeoptionen"
type: docs
weight: 5250
url: /de/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

PSD-Ladeoptionen

```csharp
public class PsdLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Liest oder setzt, ob die ursprünglichen Ebenenpixel beim Rendern erhalten bleiben sollen, wenn die Ebene nicht verändert wurde. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Liest oder setzt, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Verzerrungs-Transformation. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Liest oder setzt die Hintergrund-`Color`(../../aspose.psd/color/) des `Image`(../../aspose.psd/image/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Liest oder setzt den Datenwiederherstellungsmodus. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [ignore alpha channel] ignoriert werden soll. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die feste Breite der PSD-Textebene bei der Ausführung der UpdateText-Operation ignoriert wird. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [load effects resource] (standardmäßig wird die Ressource nicht geladen). Wenn diese Option gesetzt ist, werden nur unterstützte Effekte in das endgültige zusammengeführte Bild gerendert. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [use read only mode] verwendet wird. Dies ist ein Nur-Lese‑Modus, der für eine identische Kompatibilität mit Adobe Photoshop unterstützt wird. Wenn diese Option gesetzt ist, werden alle für Ebenen vorgenommenen Änderungen nicht im endgültigen Bild gespeichert. Alle Daten werden aus dem ImageData‑Abschnitt verwendet, sodass es identisch zu Photoshop ist. Standardmäßig sind alle geladenen Bilder nicht mit Adobe Photoshop kompatibel. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Liest oder legt den schreibgeschützten Modus fest, der beim Laden eines PSD-Bildes verwendet wird. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob [use disk for load effects resource] (standardmäßig wird die Festplatte zum Laden von Effektressourcen verwendet, kann jedoch Speicher verwendet werden, wenn dieser Wert auf false gesetzt wird). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |

## Beispiele

Das folgende Beispiel demonstriert, dass der Dokumentkonvertierungsfortschritt korrekt funktioniert und ohne Ausnahme.

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
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


