---
title: Class PatternOverlayEffect
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.PatternOverlayEffect klass. Mönsterlagereffekt
type: docs
weight: 2180
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---
## PatternOverlayEffect class

Mönsterlagereffekt

```csharp
public class PatternOverlayEffect : ILayerEffect
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/blendmode/) { get; set; } | Hämtar eller ställer in blandningsläget. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/) { get; } | Får en typ av effekt type |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/isvisible/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är synlig. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/opacity/) { get; set; } | Hämtar eller ställer in opaciteten. |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/settings/) { get; set; } | Hämtar eller ställer in inställningarna. |

### Exempel

Följande kod visar stödet för mönsteröverlagringseffekten.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (expected is Array && actual is Array)
    {
        Array array1 = (Array)expected;
        Array array2 = (Array)actual;
        AssertAreEqual(array1.Length, array2.Length);

        for (int i = 0; i < array1.Length; i++)
        {
            AssertAreEqual(array1.GetValue(i), array2.GetValue(i));
        }
        return;
    }

    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "PatternOverlay.psd";
string exportPath = "PatternOverlayChanged.psd";

var newPattern = new int[]
{
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
};

var newPatternBounds = new Rectangle(0, 0, 4, 2);
var guid = Guid.NewGuid();
var newPatternName = "$$$/Presets/Patterns/Pattern=Some new pattern name\0";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var patternOverlay = (PatternOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, patternOverlay.BlendMode);
    AssertAreEqual((byte)127, patternOverlay.Opacity);
    AssertAreEqual(true, patternOverlay.IsVisible);

    var settings = patternOverlay.Settings;
    AssertAreEqual(Color.Empty, settings.Color);
    AssertAreEqual(FillType.Pattern, settings.FillType);
    AssertAreEqual("85163837-eb9e-5b43-86fb-e6d5963ea29a".ToUpperInvariant(), settings.PatternId);
    AssertAreEqual("$$$/Presets/Patterns/OpticalSquares=Optical Squares", settings.PatternName);
    AssertAreEqual(null, settings.PointType);
    AssertAreEqual(100.00, settings.Scale);

    AssertAreEqual(true, settings.Linked);
    AssertIsTrue(Math.Abs(0 - settings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - settings.VerticalOffset) < 0.001, "Vertical offset is incorrect");

    // Testredigering
    settings.Color = Color.Green;

    patternOverlay.Opacity = 193;
    patternOverlay.BlendMode = BlendMode.Difference;
    settings.HorizontalOffset = 15;
    settings.VerticalOffset = 11;

    settings.PatternName = newPatternName;
    settings.PatternId = guid.ToString();
    settings.PatternData = newPattern;
    settings.PatternWidth = newPatternBounds.Width;
    settings.PatternHeight = newPatternBounds.Height;
    
    im.Save(exportPath);
}

// Testfil efter redigering
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var patternOverlay = (PatternOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Difference, patternOverlay.BlendMode);
    AssertAreEqual((byte)193, patternOverlay.Opacity);
    AssertAreEqual(true, patternOverlay.IsVisible);

    var fillSettings = patternOverlay.Settings;
    AssertAreEqual(Color.Empty, fillSettings.Color);
    AssertAreEqual(FillType.Pattern, fillSettings.FillType);

    PattResource resource = null;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
        }
    }

    if (resource == null)
    {
        throw new Exception("PattResource not found");
    }

    // Kontrollera mönsterdata
    AssertAreEqual(newPattern, resource.Patterns[1].PatternData);
    AssertAreEqual(newPatternBounds, new Rectangle(0, 0, resource.Patterns[1].Width, resource.Patterns[1].Height));
    AssertAreEqual(guid.ToString().ToUpperInvariant(), resource.Patterns[1].PatternId);
    AssertAreEqual(newPatternName, resource.Patterns[1].Name + "\0");
}
```

### Se även

* interface [ILayerEffect](../ilayereffect/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* hopsättning [Aspose.PSD](../../)


