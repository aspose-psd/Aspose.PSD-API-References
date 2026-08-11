---
title: "IGradientFillSettings.GradientType"
second_title: "Aspose.PSD for .NET API Reference"
description: "IGradientFillSettings プロパティ。グラデーションのタイプを取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/
---
{{< psd/tize >}}
## IGradientFillSettings.GradientType property

グラデーションのタイプを取得または設定します。

```csharp
public GradientType GradientType { get; set; }
```

### Property Value

グラデーションのタイプです。

## 例

次のコードは、異なるタイプのグラデーションで画像を保存し、Aspose.PSD がグラデーションを描画する方法を示します。

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

### 関連項目

* enum [GradientType](../../gradienttype/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


