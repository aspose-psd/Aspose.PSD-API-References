---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage メソッド。しきい値調整レイヤーを追加します"
type: docs
weight: 480
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

しきい値調整レイヤーを追加します。

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### 戻り値

作成されたしきい値調整レイヤー。

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

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


