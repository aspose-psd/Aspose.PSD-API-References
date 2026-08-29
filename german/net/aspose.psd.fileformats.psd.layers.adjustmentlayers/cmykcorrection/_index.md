---
title: "Klasse CmykCorrection"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.CmykCorrection Klasse. Farbkorrektur in einem selektiven Farbkorrektur‑Anpassungslayer."
type: docs
weight: 1750
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/cmykcorrection/
---
{{< psd/tize >}}
## CmykCorrection class

Farbkorrektur in der selektiven Farb‑Anpassungsebene.

```csharp
public class CmykCorrection
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CmykCorrection](cmykcorrection/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Black](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/cmykcorrection/black/) { get; set; } | Liest oder setzt die Korrektur der schwarzen Farbe. |
| [Cyan](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/cmykcorrection/cyan/) { get; set; } | Liest oder setzt die Korrektur der cyan‑Farbe. |
| [Magenta](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/cmykcorrection/magenta/) { get; set; } | Liest oder setzt die Korrektur der magenta‑Farbe. |
| [Yellow](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/cmykcorrection/yellow/) { get; set; } | Liest oder setzt die Korrektur der gelben Farbe. |

## Beispiele

Der folgende Code demonstriert die Unterstützung des SelectiveColorLayer‑Anpassungs‑Layers.

```csharp
[C#]

string sourceFileWithSelectiveColorLayer = "houses_selectiveColor_source.psd";
string outputPsdWithSelectiveColorLayer = "houses_selectiveColor_output.psd";
string outputPngWithSelectiveColorLayer = "houses_selectiveColor_output.png";

string sourceFileWithoutSelectiveColorLayer = "houses_source.psd";
string outputPsdWithoutSelectiveColorLayer = "houses_output.psd";
string outputPngWithoutSelectiveColorLayer = "houses_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Abrufen, prüfen und ändern Sie die Selective Color Anpassungsebene im Bild.
using (var image = (PsdImage)Image.Load(sourceFileWithSelectiveColorLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is SelectiveColorLayer)
        {
            // Abrufen der Selective Color Anpassungsebene.
            SelectiveColorLayer selcLayer = (SelectiveColorLayer)layer;
            var redCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Reds);
            var yellowCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Yellows);
            var greenCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Greens);
            var blueCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Blues);

            // Parameter der Ebenen prüfen.
            AssertAreEqual(CorrectionMethodTypes.Absolute, selcLayer.CorrectionMethod);

            AssertAreEqual(redCorrection.Cyan, (short)-31);
            AssertAreEqual(redCorrection.Magenta, (short)-12);
            AssertAreEqual(redCorrection.Yellow, (short)27);
            AssertAreEqual(redCorrection.Black, (short)33);

            AssertAreEqual(yellowCorrection.Cyan, (short)-22);
            AssertAreEqual(yellowCorrection.Magenta, (short)-19);
            AssertAreEqual(yellowCorrection.Yellow, (short)8);
            AssertAreEqual(yellowCorrection.Black, (short)0);

            AssertAreEqual(greenCorrection.Cyan, (short)0);
            AssertAreEqual(greenCorrection.Magenta, (short)0);
            AssertAreEqual(greenCorrection.Yellow, (short)0);
            AssertAreEqual(greenCorrection.Black, (short)0);

            AssertAreEqual(blueCorrection.Cyan, (short)58);
            AssertAreEqual(blueCorrection.Magenta, (short)18);
            AssertAreEqual(blueCorrection.Yellow, (short)1);
            AssertAreEqual(blueCorrection.Black, (short)7);

            // Parameter der Ebenen ändern.
            selcLayer.CorrectionMethod = CorrectionMethodTypes.Relative;
            selcLayer.SetCmykCorrection(SelectiveColorsTypes.Reds,
                new CmykCorrection { Cyan = 12, Magenta = -20, Yellow = 10, Black = -15 });
            selcLayer.SetCmykCorrection(SelectiveColorsTypes.Whites,
                new CmykCorrection { Cyan = 15, Magenta = 20, Yellow = -75, Black = 42 });

            image.Save(outputPsdWithSelectiveColorLayer);
            image.Save(outputPngWithSelectiveColorLayer, new PngOptions());
        }
    }
}

// Selective Color Anpassungsebene zum Bild hinzufügen und festlegen.
using (var image = (PsdImage)Image.Load(sourceFileWithoutSelectiveColorLayer))
{
    // Selective Color Anpassungsebene hinzufügen.
    SelectiveColorLayer selectiveColorLayer = image.AddSelectiveColorAdjustmentLayer();

    // Parameter der Ebenen festlegen.
    selectiveColorLayer.CorrectionMethod = CorrectionMethodTypes.Absolute;
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Whites,
        new CmykCorrection { Cyan = 100, Magenta = -100, Yellow = 100, Black = 0 });
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Blacks,
        new CmykCorrection { Cyan = 10, Magenta = 15, Yellow = 17, Black = -3 });
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Neutrals,
        new CmykCorrection { Cyan = 45, Magenta = 21, Yellow = -14, Black = 0 });
    selectiveColorLayer.SetCmykCorrection(SelectiveColorsTypes.Magentas,
        new CmykCorrection { Cyan = 8, Magenta = -10, Yellow = -14, Black = 25 });

    image.Save(outputPsdWithoutSelectiveColorLayer);
    image.Save(outputPngWithoutSelectiveColorLayer, new PngOptions());
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


