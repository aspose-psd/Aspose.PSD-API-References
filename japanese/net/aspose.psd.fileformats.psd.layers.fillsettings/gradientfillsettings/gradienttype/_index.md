---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD for .NET API リファレンス
description: GradientFillSettings 財産. グラデーションのタイプを取得または設定します
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

グラデーションのタイプを取得または設定します。

```csharp
public GradientType GradientType { get; set; }
```

### プロパティ値

グラデーションのタイプ。

### 例

次のコードは、さまざまなタイプのグラデーションで画像を保存し、Aspose.PSD がグラデーションを描画する方法を示しています。

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
* class [GradientFillSettings](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* 組み立て [Aspose.PSD](../../../)


