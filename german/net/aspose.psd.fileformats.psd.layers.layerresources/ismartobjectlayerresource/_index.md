---
title: "Schnittstelle ISmartObjectLayerResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ISmartObjectLayerResource Schnittstelle. Definiert die ISmartObjectLayerResource Schnittstelle, die Informationen über eine Smart‑Object‑Ebenenressource in der PSD‑Datei enthält. Sie ist außerdem eine Markup‑Schnittstelle, die verwendet wird, um sowohl Sold als auch Sole Ressourcen in den Adobe Photoshop Bildern zu kennzeichnen."
type: docs
weight: 2830
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/
---
{{< psd/tize >}}
## ISmartObjectLayerResource interface

Definiert die Schnittstelle **ISmartObjectLayerResource**, die Informationen über eine Smart‑Object‑Ebenen‑Ressource in der PSD‑Datei enthält. Es ist außerdem eine Markup‑Schnittstelle, die verwendet wird, um sowohl Sold‑ als auch Sole‑Ressourcen in den Adobe® Photoshop®‑Bildern zu kennzeichnen.

```csharp
public interface ISmartObjectLayerResource : IPlacedLayerResource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/) { get; set; } | Liest oder setzt den eindeutigen Bezeichner dieser Smart‑Object‑Ebenendaten im PSD‑Bild. |

## Beispiele

Der folgende Code demonstriert die Unterstützung eingebetteter Smart‑Objekte.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Dieses Beispiel zeigt, wie man die Smart‑Object‑Ebene in der PSD‑Datei ändert und die ursprünglichen eingebetteten Inhalte des Smart‑Objects exportiert / aktualisiert.
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

        // Exportieren wir das eingebettete Smart‑Object‑Bild aus der PSD‑Smart‑Object‑Ebene.
        smartObjectLayer.ExportContents(exportPath);

        // Überprüfen wir, ob das Originalbild korrekt gespeichert wurde
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Lassen Sie das ursprüngliche Smart‑Object‑Bild invertieren
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Lassen Sie das eingebettete Smart‑Object‑Bild in der PSD‑Ebene ersetzen
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Lassen Sie prüfen, ob das aktualisierte Bild korrekt gespeichert wurde
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Siehe auch

* interface [IPlacedLayerResource](../iplacedlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


