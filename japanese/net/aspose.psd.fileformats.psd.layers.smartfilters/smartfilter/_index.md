---
title: Class SmartFilter
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SmartFilter クラス. スマートフィルターの基本ロジックを処理するクラス.
type: docs
weight: 3460
url: /ja/net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---
## SmartFilter class

スマートフィルターの基本ロジックを処理するクラス.

```csharp
public abstract class SmartFilter : ICloneable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SmartFilter](smartfilter/)() | の新しいインスタンスを初期化します`SmartFilter`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | ブレンド モードを取得または設定します。 |
| abstract [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/filterid/) { get; } | スマート フィルター タイプ識別子を取得します。 |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | スマート フィルターの有効な状態を取得または設定します。 |
| abstract [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/name/) { get; } | スマートフィルター名を取得します. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | スマート フィルターの不透明度の値を取得または設定します。 |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | スマート フィルター データを含むソース記述子構造。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | 現在のフィルターを入力に適用します[`RasterImage`](../../aspose.psd/rasterimage/)image. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | 現在のフィルターを入力に適用します[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/)マスクデータ. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | 型の現在のインスタンスのメンバー単位のクローンを作成します。 |

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


