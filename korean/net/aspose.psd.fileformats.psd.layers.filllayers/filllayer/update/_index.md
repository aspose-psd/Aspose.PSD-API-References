---
title: FillLayer.Update
second_title: .NET API 참조용 Aspose.PSD
description: FillLayer 방법. 실제에 따라 채우기 레이어 픽셀 데이터를 업데이트합니다.IFillSettings .
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/
---
## FillLayer.Update method

실제에 따라 채우기 레이어 픽셀 데이터를 업데이트합니다.[`IFillSettings`](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) .

```csharp
public void Update()
```

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | 알 수 없는 유형의 FillType |

### 예

다음 코드는 채우기 레이어 지원을 보여줍니다. 색상 채우기.

```csharp
[C#]

// 채우기 레이어 지원 추가: 색상 채우기
string sourceFileName = "ColorFillLayer.psd";
string exportPath = "ColorFillLayer_output.psd";

var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Color)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (IColorFillSettings)fillLayer.FillSettings;
            settings.Color = Color.Red;
            fillLayer.Update();
            im.Save(exportPath);
            break;
        }
    }
}
```

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

다음 코드는 패턴 채우기 레이어로 이미지를 저장하고 Aspose.PSD가 패턴을 렌더링하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
using (var image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var layer in image.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var settings = (IPatternFillSettings)fillLayer.FillSettings;
            settings.HorizontalOffset = -5;
            settings.VerticalOffset = 12;
            settings.Scale = 300;
            settings.Linked = true;
            settings.PatternData = new int[]
                                       {
                                           Color.Black.ToArgb(), Color.Red.ToArgb(),
                                           Color.Green.ToArgb(), Color.Blue.ToArgb(),
                                           Color.White.ToArgb(), Color.AliceBlue.ToArgb(),
                                           Color.Violet.ToArgb(), Color.Chocolate.ToArgb(),
                                           Color.IndianRed.ToArgb(), Color.DarkOliveGreen.ToArgb(),
                                           Color.CadetBlue.ToArgb(), Color.YellowGreen.ToArgb(),
                                           Color.Black.ToArgb(), Color.Azure.ToArgb(),
                                           Color.ForestGreen.ToArgb(), Color.Sienna.ToArgb(),
                                       };

            settings.PatternHeight = 4;
            settings.PatternWidth = 4;

            settings.PatternName = "$$$/Presets/Patterns/ColorfulSquare=Colorful Square New\0";
            settings.PatternId = Guid.NewGuid().ToString() + "\0";

            fillLayer.Update();
            break;
        }
    }

    image.Save(outputFile, new PsdOptions(image));
    image.Save(outputPngFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또한보십시오

* class [FillLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 집회 [Aspose.PSD](../../../)


