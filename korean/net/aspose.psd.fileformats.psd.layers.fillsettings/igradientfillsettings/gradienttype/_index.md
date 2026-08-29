---
title: "IGradientFillSettings.GradientType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "IGradientFillSettings 속성. 그라디언트 유형을 가져오거나 설정합니다."
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/
---
{{< psd/tize >}}
## IGradientFillSettings.GradientType property

그라디언트의 유형을 가져오거나 설정합니다.

```csharp
public GradientType GradientType { get; set; }
```

### Property Value

그라디언트 유형.

## 예제

다음 코드는 다양한 유형의 그라디언트를 사용하여 이미지를 저장하고 Aspose.PSD가 그라디언트를 그리는 방법을 보여줍니다.

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

### 또 보기

* enum [GradientType](../../gradienttype/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


