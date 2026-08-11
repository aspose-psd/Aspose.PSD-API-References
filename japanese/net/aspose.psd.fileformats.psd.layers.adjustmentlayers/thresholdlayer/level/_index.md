---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD for .NET API Reference"
description: "ThresholdLayer プロパティ。しきい値レベルを取得および設定します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

しきい値レベルを取得および設定します。

```csharp
public short Level { get; set; }
```

### Property Value

レベルです。

## 例

以下のコードは ThresholdLayer 調整レイヤーのサポートを示しています。

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 画像から Threshold 調整レイヤーを取得、確認、変更します。
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Threshold 調整レイヤーを取得します。
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // レイヤーのパラメータを確認します。
            AssertAreEqual(level, (short)115);

            // レイヤーのパラメータを設定します。
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// 画像に Threshold 調整レイヤーを追加および設定します。
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Threshold 調整レイヤーを追加します。
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // レイヤーのパラメータを設定します。
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### 関連項目

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


