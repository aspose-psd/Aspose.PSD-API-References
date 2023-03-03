---
title: Enum NoiseDistribution
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.NoiseDistribution 列挙. ノイズフィルターの分布.
type: docs
weight: 3440
url: /ja/net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution/
---
## NoiseDistribution enumeration

ノイズフィルターの分布.

```csharp
public enum NoiseDistribution
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Uniform | `0` | 一様なノイズ分布. |
| Gaussian | `1` | ガウス ノイズ分布。 |

### 例

この例は、スマート フィルター インターフェイスのサポートを示しています。

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // スマート フィルターを編集します
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // フィルタ値をチェック
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // フィルター値を更新します
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // 新しいフィルタ項目を追加
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // 変更を適用
    smartObj.SmartFilters.UpdateResourceValues();

    // フィルタを適用
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // フィルタ値をチェック
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* 組み立て [Aspose.PSD](../../)


