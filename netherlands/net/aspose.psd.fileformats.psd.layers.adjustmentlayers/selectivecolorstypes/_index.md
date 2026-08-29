---
title: "Enum SelectiveColorsTypes"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.SelectiveColorsTypes enum. Kleurtypes in selectieve kleur-aanpassingslaag"
type: docs
weight: 1910
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorstypes/
---
{{< psd/tize >}}
## SelectiveColorsTypes enumeration

Kleurtypes in selectieve kleur-aanpassingslaag.

```csharp
public enum SelectiveColorsTypes
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Reds | `0` | De rode kleuren. |
| Yellows | `1` | De gele kleuren. |
| Greens | `2` | De groene kleuren. |
| Cyans | `3` | De cyaankleuren. |
| Blues | `4` | De blauwe kleuren. |
| Magentas | `5` | De magentakleuren. |
| Whites | `6` | De witte kleuren. |
| Neutrals | `7` | De neutrale kleuren. |
| Blacks | `8` | De zwarte kleuren. |

## Voorbeelden

De volgende code demonstreert de ondersteuning van de SelectiveColorLayer-aanpassingslaag.

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

// Haal, controleer en wijzig de Selective Color-aanpassingslaag van de afbeelding.
using (var image = (PsdImage)Image.Load(sourceFileWithSelectiveColorLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is SelectiveColorLayer)
        {
            // Haal Selective Color-aanpassingslaag op.
            SelectiveColorLayer selcLayer = (SelectiveColorLayer)layer;
            var redCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Reds);
            var yellowCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Yellows);
            var greenCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Greens);
            var blueCorrection = selcLayer.GetCmykCorrection(SelectiveColorsTypes.Blues);

            // Controleer laagparameters.
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

            // Wijzig laagparameters.
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

// Voeg de Selective color-aanpassingslaag toe aan de afbeelding en stel deze in.
using (var image = (PsdImage)Image.Load(sourceFileWithoutSelectiveColorLayer))
{
    // Voeg Selective Color Adjustment layer toe.
    SelectiveColorLayer selectiveColorLayer = image.AddSelectiveColorAdjustmentLayer();

    // Stel laagparameters in.
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

### Zie ook

* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


