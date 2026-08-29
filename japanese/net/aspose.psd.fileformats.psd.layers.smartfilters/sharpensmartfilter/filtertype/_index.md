---
title: "SharpenSmartFilter.FilterType"
second_title: "Aspose.PSD for .NET API Reference"
description: "SharpenSmartFilter フィールド。現在のスマートフィルタの識別子です。"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/
---
{{< psd/tize >}}
## SharpenSmartFilter.FilterType field

現在のスマートフィルタの識別子です。

```csharp
public const int FilterType;
```

## 例

以下のコードは SharpenSmartFilter のサポートを示しています。

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // スマートフィルタを編集
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // フィルタ値を確認
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // フィルタ値を更新
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // 新しいフィルタ項目を追加
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // 変更を適用
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 関連項目

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


