---
title: "PatternFillSettings.AlignWithLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PatternFillSettings özelliği. Katmanla bağlantı olup olmadığını gösteren bir değeri alır veya ayarlar"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/alignwithlayer/
---
{{< psd/tize >}}
## PatternFillSettings.AlignWithLayer property

Katmanla [link with layer] bağlantısını gösteren bir değeri alır veya ayarlar.

```csharp
public bool AlignWithLayer { get; set; }
```

### Property Value

`true` ise [katmanla bağlantı]; aksi takdirde `false`.

## Örnekler

Aşağıdaki kod, Doldurma Katmanı Desen düzenlemesinin desteğini gösterir.

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

            // Düzenleme 
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

### Ayrıca Bakınız

* class [PatternFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


