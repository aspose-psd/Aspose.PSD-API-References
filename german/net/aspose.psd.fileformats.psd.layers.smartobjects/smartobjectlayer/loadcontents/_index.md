---
title: SmartObjectLayer.LoadContents
second_title: Aspose.PSD für .NET-API-Referenz
description: SmartObjectLayer methode. Ruft die eingebetteten oder verknüpften Bildinhalte der SmartObjektEbene ab.
type: docs
weight: 110
url: /de/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/
---
## SmartObjectLayer.LoadContents method

Ruft die eingebetteten oder verknüpften Bildinhalte der Smart-Objekt-Ebene ab.

```csharp
public Image LoadContents(LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | LoadOptions | Die Optionen. |

### Rückgabewert

Die geladen[`Image`](../../../aspose.psd/image/) intelligente Objektinstanz.

### Beispiele

Der folgende Code demonstriert die Unterstützung eingebetteter Smart-Objekte.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Dieses Beispiel zeigt, wie die Smart-Objekt-Ebene in der PSD-Datei geändert und der ursprünglich eingebettete Inhalt des Smart-Objekts exportiert/aktualisiert wird.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Lassen Sie uns das eingebettete Smart-Objekt-Bild aus der PSD-Smart-Objekt-Ebene exportieren
        smartObjectLayer.ExportContents(exportPath);

        // Prüfen wir, ob das Originalbild korrekt gespeichert wurde
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Lassen Sie uns das ursprüngliche Smart-Objekt-Bild invertieren
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Lassen Sie uns das eingebettete Smart-Objekt-Bild in der PSD-Ebene ersetzen
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Prüfen wir, ob das aktualisierte Bild korrekt gespeichert wird
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Siehe auch

* class [Image](../../../aspose.psd/image/)
* class [LoadOptions](../../../aspose.psd/loadoptions/)
* class [SmartObjectLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* Montage [Aspose.PSD](../../../)


