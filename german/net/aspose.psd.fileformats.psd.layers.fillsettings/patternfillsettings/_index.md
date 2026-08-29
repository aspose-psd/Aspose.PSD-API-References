---
title: "Klasse PatternFillSettings"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.PatternFillSettings Klasse. Einstellungen für den Musterfüllungseffekt"
type: docs
weight: 2170
url: /de/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---
{{< psd/tize >}}
## PatternFillSettings class

Musterfüllungseffekt‑Einstellungen

```csharp
public class PatternFillSettings : BaseFillSettings, IPatternFillSettings
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PatternFillSettings](patternfillsettings/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/alignwithlayer/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [link with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/angle/) { get; set; } | Liest oder setzt den Winkel. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/color/) { get; set; } | Liest oder setzt die Farbe. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/filltype/) { get; } | Der Fülltyp |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/horizontaloffset/) { get; set; } | Liest oder setzt den horizontalen Versatz. |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/linked/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob dieses `PatternFillSettings` verknüpft ist. |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patterndata/) { get; set; } | Liest oder setzt die Musterdaten. |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternheight/) { get; set; } | Liest oder setzt die Höhe des Musters. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternid/) { get; set; } | Liest oder setzt die Musterkennung. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternname/) { get; set; } | Liest oder setzt den Namen des Musters. |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/patternwidth/) { get; set; } | Liest oder setzt die Breite des Musters. |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/pointtype/) { get; set; } | Liest oder setzt den Typ des Punktes. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/scale/) { get; set; } | Liest oder setzt die Skala. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/verticaloffset/) { get; set; } | Liest oder setzt den vertikalen Versatz. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/generatelfx2resourcenodes/)(string, Color, string, string, double, bool, PointF) | Erzeugt die LFX2-Ressourcenknoten. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der Bearbeitung des Fill Layer Pattern.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PatternFillLayer_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            FillLayer fillLayer = (FillLayer)layer;
            PatternFillSettings fillSettings = (PatternFillSettings)fillLayer.FillSettings;

            if (fillSettings.HorizontalOffset != -46 ||
                fillSettings.VerticalOffset != -45 ||
                fillSettings.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5".ToUpperInvariant() ||
                fillSettings.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares" ||
                fillSettings.AlignWithLayer != true ||
                fillSettings.Linked != true ||
                fillSettings.PatternHeight != 64 ||
                fillSettings.PatternWidth != 64 ||
                fillSettings.PatternData.Length != 4096 ||
                Math.Abs(fillSettings.Scale - 50) > tolerance)
            {
                throw new Exception("PSD Image was read wrong");
            }

            // Bearbeitung 
            fillSettings.Scale = 300;
            fillSettings.HorizontalOffset = 2;
            fillSettings.VerticalOffset = -20;
            fillSettings.PatternData = new int[]
            {
                Color.Red.ToArgb(), Color.Blue.ToArgb(),  Color.Blue.ToArgb(),
                Color.Blue.ToArgb(), Color.Red.ToArgb(),  Color.Blue.ToArgb(),
                Color.Blue.ToArgb(), Color.Blue.ToArgb(),  Color.Red.ToArgb()
            };
            fillSettings.PatternHeight = 3;
            fillSettings.PatternWidth = 3;
            fillSettings.AlignWithLayer = false;
            fillSettings.Linked = false;
            fillSettings.PatternId = Guid.NewGuid().ToString();
            fillLayer.Update();
            break;
        }
    }
    im.Save(exportPath);
}
```

Der folgende Code demonstriert die Unterstützung der Strich-Effekt-Ebene mit Fülltyp - Pattern.

```csharp
[C#]

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

string sourceFileName = "Stroke.psd";
string exportPath = "StrokePatternChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

// Neue Daten vorbereiten
var newPattern = new int[]
{
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
};

var newPatternBounds = new Rectangle(0, 0, 4, 4);
var guid = Guid.NewGuid();

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, patternStroke.BlendMode);
    AssertAreEqual((byte)255, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;
    AssertAreEqual(FillType.Pattern, fillSettings.FillType);

    patternStroke.Opacity = 127;
    patternStroke.BlendMode = BlendMode.Color;

    PattResource resource;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
            resource.Patterns[0].PatternId = guid.ToString();
            resource.Patterns[0].Name = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

            resource.Patterns[0].SetPattern(newPattern, newPatternBounds);
        }
    }

    ((PatternFillSettings)patternStroke.FillSettings).PatternName = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

    ((PatternFillSettings)patternStroke.FillSettings).PatternId = guid.ToString() + "\0";
    im.Save(exportPath);
}

// Testdatei nach Bearbeitung
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

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

    // Prüfen Sie die Musterdaten
    AssertAreEqual(newPattern, resource.Patterns[0].PatternData);
    AssertAreEqual(newPatternBounds, new Rectangle(0, 0, resource.Patterns[0].Width, resource.Patterns[0].Height));
    AssertAreEqual(guid.ToString().ToUpperInvariant(), resource.Patterns[0].PatternId);

    AssertAreEqual(BlendMode.Color, patternStroke.BlendMode);
    AssertAreEqual((byte)127, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;

    AssertAreEqual(FillType.Pattern, fillSettings.FillType);
}
```

### Siehe auch

* class [BaseFillSettings](../basefillsettings/)
* interface [IPatternFillSettings](../ipatternfillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


