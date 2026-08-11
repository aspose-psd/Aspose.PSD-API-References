---
title: "クラス PixelsData"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.PixelsData クラス。画像ピクセルデータとその境界を格納するクラスです。"
type: docs
weight: 5740
url: /ja/net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

画像ピクセルデータとその境界を格納するクラスです。

```csharp
public sealed class PixelsData : ICloneable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | `PixelsData` クラスの新しいインスタンスを初期化します。 |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | `PixelsData` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | ピクセル データの境界を取得または設定します。 |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | ピクセル データを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../aspose.psd/pixelsdata/clone/)() | インスタンスの完全なコピーを作成します。 |

## 例

以下のコードは、カスタムレンダラーを持つカスタムスマートフィルターの作成方法を示しています。

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // 入力配列でサポートされていない「Crystallize」スマートフィルターを初期化します
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 「Crystallize」スマートフィルターの ID。
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // SmartObject にフィルターを適用する
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // レイヤーマスクにフィルターを適用する
        smartFilter.ApplyToMask(maskLayer);

        //レイヤーにフィルターを適用する
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // 「Crystallize」スマートフィルターの ID。
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // フィルター構造を取得する
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Crystallize サイズの値を取得する
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


