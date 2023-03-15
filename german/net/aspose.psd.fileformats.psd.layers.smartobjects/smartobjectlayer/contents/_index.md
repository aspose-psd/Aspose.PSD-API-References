---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD für .NET-API-Referenz
description: SmartObjectLayer eigendom. Ruft den Inhalt der SmartObjektEbene ab oder legt ihn fest. Der Inhalt des eingebetteten SmartObjekts ist die eingebettete RohbilddateiData und seine Eigenschaften. Der Inhalt des verknüpften SmartObjekts ist der Rohinhalt der verknüpften Bilddatei sofern verfügbar und seine EigenschaftenLiFeDataSource . Wir unterstützen das Laden aus der Adobe Photoshop  Grafikbibliothek nicht wennIsLibraryLink ist wahr. Für normale LinkDateien verwenden wir zunächstRelativePath um die Datei relativ zum Quellbildpfad zu suchenSourceImagePath  wenn es nicht verfügbar ist schauen wir uns anFullPath  Wenn nicht suchen wir die Linkdatei im selben Verzeichnis in dem sich unser Bild befindetSourceImagePath .
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Ruft den Inhalt der Smart-Objekt-Ebene ab oder legt ihn fest. Der Inhalt des eingebetteten Smart-Objekts ist die eingebettete Rohbilddatei:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) und seine Eigenschaften. Der Inhalt des verknüpften Smart-Objekts ist der Rohinhalt der verknüpften Bilddatei, sofern verfügbar, und seine Eigenschaften:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Wir unterstützen das Laden aus der Adobe� Photoshop� �� Grafikbibliothek nicht, wenn[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) ist wahr. Für normale Link-Dateien verwenden wir zunächst[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) um die Datei relativ zum Quellbildpfad zu suchenSourceImagePath , wenn es nicht verfügbar ist, schauen wir uns an[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , Wenn nicht, suchen wir die Linkdatei im selben Verzeichnis, in dem sich unser Bild befindet:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Eigentumswert

Diebyte[] Inhalt der intelligenten Objektebene.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| NotSupportedException | Inhalte aus der Adobe� Photoshop� ��-Bibliothek können nicht abgerufen werden. |

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

* class [SmartObjectLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* Montage [Aspose.PSD](../../../)


