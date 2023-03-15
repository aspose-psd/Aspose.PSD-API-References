---
title: GradientFillSettings.GradientType
second_title: .NET API 참조용 Aspose.PSD
description: GradientFillSettings 재산. 그라데이션 유형을 가져오거나 설정합니다.
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

그라데이션 유형을 가져오거나 설정합니다.

```csharp
public GradientType GradientType { get; set; }
```

### 자산 가치

그라데이션 유형입니다.

### 예

다음 코드는 다양한 유형의 그래디언트로 이미지를 저장하고 Aspose.PSD가 그래디언트를 그리는 방법을 보여줍니다.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 또한보십시오

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* 집회 [Aspose.PSD](../../../)


