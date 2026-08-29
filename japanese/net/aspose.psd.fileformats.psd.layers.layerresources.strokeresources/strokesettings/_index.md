---
title: "クラス StrokeSettings"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.StrokeSettings クラス。シェイプのストローク設定"
type: docs
weight: 3420
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/
---
{{< psd/tize >}}
## StrokeSettings class

シェイプのストローク設定です。

```csharp
public class StrokeSettings : IStrokeSettings
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StrokeSettings](strokesettings/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/enabled/) { get; set; } | ストロークが有効かどうかを取得または設定します。 |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/fill/) { get; set; } | ストロークの塗り設定を取得または設定します。 |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linealignment/) { get; set; } | ストロークスタイルのライン配置を取得または設定します。 |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linecap/) { get; set; } | ストロークのラインキャップの種類を取得または設定します。 |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linedashset/) { get; set; } | ラインダッシュの配列を取得または設定します。 |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linejoin/) { get; set; } | ストロークのラインジョインの種類を取得または設定します。 |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/size/) { get; set; } | ストロークライン幅を取得または設定します。 |

## 例

以下のコードはシェイプストロークのレンダリングサポートを示しています。

```csharp
[C#]

string sourceFile = "StrokeShapeTest.psd";
string outputFilePsd = "StrokeShapeTest.out.psd";
string outputFilePng = "StrokeShapeTest.out.png";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer = image.Layers[1];
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.GreenYellow;
    shapeLayer.Update();

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    gradientSettings.Dither = true;
    gradientSettings.Reverse = true;
    gradientSettings.AlignWithLayer = false;
    gradientSettings.Angle = 20;
    gradientSettings.Scale = 50;
    solidGradient.ColorPoints[0].Location = 100;
    solidGradient.ColorPoints[1].Location = 4000;
    solidGradient.TransparencyPoints[0].Location = 200;
    solidGradient.TransparencyPoints[1].Location = 3800;
    solidGradient.TransparencyPoints[0].Opacity = 90;
    solidGradient.TransparencyPoints[1].Opacity = 10;
    shapeLayer2.Update();

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    strokeSettings.Size = 15;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    strokeFillSettings.Color = Color.GreenYellow;
    shapeLayer3.Update();

    image.Save(outputFilePsd);
    image.Save(outputFilePng, new PngOptions());
}

// 変更されたデータを確認します。
using (PsdImage image = (PsdImage)Image.Load(outputFilePsd))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    AssertAreEqual(Color.GreenYellow, fillSettings.Color);

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    AssertAreEqual(true, gradientSettings.Dither);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.AlignWithLayer);
    AssertAreEqual(20.0, gradientSettings.Angle);
    AssertAreEqual(50, gradientSettings.Scale);
    AssertAreEqual(100, solidGradient.ColorPoints[0].Location);
    AssertAreEqual(4000, solidGradient.ColorPoints[1].Location);
    AssertAreEqual(200, solidGradient.TransparencyPoints[0].Location);
    AssertAreEqual(3800, solidGradient.TransparencyPoints[1].Location);
    AssertAreEqual(90.0, solidGradient.TransparencyPoints[0].Opacity);
    AssertAreEqual(10.0, solidGradient.TransparencyPoints[1].Opacity);

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    AssertAreEqual(15.0, strokeSettings.Size);
    AssertAreEqual(Color.GreenYellow, strokeFillSettings.Color);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 関連項目

* interface [IStrokeSettings](../istrokesettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


