---
title: Class PixelsData
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.PixelsData クラス. 画像ピクセル データとその境界を格納するクラス
type: docs
weight: 5250
url: /ja/net/aspose.psd/pixelsdata/
---
## PixelsData class

画像ピクセル データとその境界を格納するクラス。

```csharp
public sealed class PixelsData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | の新しいインスタンスを初期化します`PixelsData`class. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | の新しいインスタンスを初期化します`PixelsData`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | ピクセル データの境界を取得または設定します。 |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | ピクセル データを取得または設定します。 |

### 例

次のコードは、カスタム レンダラーを持つカスタム スマート フィルターを作成する方法を示しています。

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // 入力配列でサポートされていない 'Crystallize' スマート フィルターを初期化します
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // 'Crystallize' スマート フィルター ID。
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

        // SmartObject にフィルタを適用します
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // レイヤーマスクにフィルターを適用
        smartFilter.ApplyToMask(maskLayer);

        //レイヤーにフィルターを適用
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
        // 'Crystallize' スマート フィルター ID。
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // フィルタ構造を取得
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Crystallize Size の値を取得
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

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


