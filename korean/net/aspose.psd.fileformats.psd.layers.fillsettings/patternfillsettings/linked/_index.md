---
title: PatternFillSettings.Linked
second_title: .NET API 참조용 Aspose.PSD
description: PatternFillSettings 재산. 이 여부를 나타내는 값을 가져오거나 설정합니다.PatternFillSettings연결되어 있습니다.
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/linked/
---
## PatternFillSettings.Linked property

이 여부를 나타내는 값을 가져오거나 설정합니다.[`PatternFillSettings`](../)연결되어 있습니다.

```csharp
public bool Linked { get; set; }
```

### 자산 가치

`진실` 연결된 경우; 그렇지 않으면,`거짓` .

### 예

다음 코드는 채우기 레이어 패턴 편집 지원을 보여줍니다.

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

            // 편집 
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

### 또한보십시오

* class [PatternFillSettings](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../patternfillsettings/)
* 집회 [Aspose.PSD](../../../)


