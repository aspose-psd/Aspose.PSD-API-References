---
title: PatternFillSettings.Linked
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PatternFillSettings संपत्त. एक मन प्रप्त करत है य सेट करत है ज दर्शत है क यहPatternFillSettingsजुड़ हुआ है.
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/linked/
---
## PatternFillSettings.Linked property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह[`PatternFillSettings`](../)जुड़ा हुआ है.

```csharp
public bool Linked { get; set; }
```

### संपत्ति मूल्य

`सत्य` अगर जुड़ा हुआ है; अन्यथा,`असत्य` .

### उदाहरण

निम्नलिखित कोड भरण परत पैटर्न संपादन के समर्थन को प्रदर्शित करता है।

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

            // संपादन 
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

### यह सभी देखें

* class [PatternFillSettings](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../patternfillsettings/)
* सभा [Aspose.PSD](../../../)


