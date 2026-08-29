---
title: "ISmartFilterRenderer.Render"
second_title: "Aspose.PSD for .NET API Reference"
description: "ISmartFilterRenderer メソッド。現在のスマートフィルタをピクセルデータにレンダリングします"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
{{< psd/tize >}}
## ISmartFilterRenderer.Render method

現在のスマートフィルターをピクセルデータにレンダリングします。

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelsData | PixelsData | ピクセルデータです。 |

### 戻り値

処理されたピクセルデータを返します。

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

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../../)


