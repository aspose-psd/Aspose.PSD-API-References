---
title: PixelsData.PixelsData
second_title: Aspose.PSD for .NET API リファレンス
description: PixelsData コンストラクタ. の新しいインスタンスを初期化しますPixelsDataclass.
type: docs
weight: 10
url: /ja/net/aspose.psd/pixelsdata/pixelsdata/
---
## PixelsData() {#constructor}

の新しいインスタンスを初期化します[`PixelsData`](../)class.

```csharp
public PixelsData()
```

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

* class [PixelsData](../)
* 名前空間 [Aspose.PSD](../../pixelsdata/)
* 組み立て [Aspose.PSD](../../../)

---

## PixelsData(int[], Rectangle) {#constructor_1}

の新しいインスタンスを初期化します[`PixelsData`](../)class.

```csharp
public PixelsData(int[] pixels, Rectangle bounds)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pixels | Int32[] | ピクセルデータ。 |
| bounds | Rectangle | ピクセルは四角形を囲んでいます。 |

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

* struct [Rectangle](../../rectangle/)
* class [PixelsData](../)
* 名前空間 [Aspose.PSD](../../pixelsdata/)
* 組み立て [Aspose.PSD](../../../)


