---
title: PatternFillSettings.Linked
second_title: Aspose.PSD για Αναφορά API .NET
description: PatternFillSettings ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτόPatternFillSettingsείναι συνδεδεμένο.
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/linked/
---
## PatternFillSettings.Linked property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό[`PatternFillSettings`](../)είναι συνδεδεμένο.

```csharp
public bool Linked { get; set; }
```

### Αξία περιουσίας

`αληθής` αν συνδεεται? σε διαφορετική περίπτωση,`ψευδής` .

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη της επεξεργασίας του μοτίβου στρώματος γεμίσματος.

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

            // Επεξεργασία 
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

### Δείτε επίσης

* class [PatternFillSettings](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../patternfillsettings/)
* συνέλευση [Aspose.PSD](../../../)


