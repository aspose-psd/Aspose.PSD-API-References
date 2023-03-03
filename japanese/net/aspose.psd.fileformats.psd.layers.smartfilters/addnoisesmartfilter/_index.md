---
title: Class AddNoiseSmartFilter
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.AddNoiseSmartFilter クラス. AddNoise スマート フィルター
type: docs
weight: 3420
url: /ja/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---
## AddNoiseSmartFilter class

AddNoise スマート フィルター。

```csharp
public sealed class AddNoiseSmartFilter : SmartFilter
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [AddNoiseSmartFilter](addnoisesmartfilter/)() | の新しいインスタンスを初期化します`AddNoiseSmartFilter`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AmountNoise](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/amountnoise/) { get; set; } | ノイズ値の量を取得または設定します。 |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | ブレンド モードを取得または設定します。 |
| [Distribution](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution/) { get; set; } | ノイズ フィルターの分布を取得または設定します。 |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filterid/) { get; } | スマート フィルター タイプ識別子を取得します。 |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | スマート フィルターの有効な状態を取得または設定します。 |
| [IsMonochromatic](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/ismonochromatic/) { get; set; } | 単色の値を取得または設定します。 |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/name/) { get; } | スマートフィルター名を取得します. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | スマート フィルターの不透明度の値を取得または設定します。 |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | スマート フィルター データを含むソース記述子構造。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | 現在のフィルターを入力に適用します[`RasterImage`](../../aspose.psd/rasterimage/)image. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | 現在のフィルターを入力に適用します[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/)マスクデータ. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | 型の現在のインスタンスのメンバー単位のクローンを作成します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filtertype/) | 現在のスマートフィルターの識別子. |

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

* class [SmartFilter](../smartfilter/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* 組み立て [Aspose.PSD](../../)


