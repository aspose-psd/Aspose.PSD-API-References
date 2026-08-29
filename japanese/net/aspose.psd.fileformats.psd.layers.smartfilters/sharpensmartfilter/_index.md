---
title: "クラス SharpenSmartFilter"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter クラス。シャープスマートフィルタ"
type: docs
weight: 3870
url: /ja/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Sharpen スマートフィルターです。

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | `SharpenSmartFilter` クラスの新しいインスタンスを初期化します。 |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | `SharpenSmartFilter` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | ブレンドモードを取得または設定します。 |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | スマートフィルタタイプ識別子を取得します。 |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | スマートフィルタの有効状態を取得または設定します。 |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | スマートフィルタ名を取得します。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | スマートフィルタの不透明度値を取得または設定します。 |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | スマートフィルタデータを含むソース記述子構造体です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | 現在のフィルタを入力[`RasterImage`](../../aspose.psd/rasterimage/)画像に適用します。 |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | 現在のフィルタを入力[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/)マスクデータに適用します。 |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | この型の現在のインスタンスのメンバ単位クローンを作成します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | 現在のスマートフィルタの識別子です。 |

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

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


