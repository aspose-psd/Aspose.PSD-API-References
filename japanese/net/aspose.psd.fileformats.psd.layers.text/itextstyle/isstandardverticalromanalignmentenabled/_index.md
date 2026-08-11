---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD for .NET API Reference"
description: "ITextStyle プロパティ。標準の垂直ローマン配置を取得または設定します。これは BaselineDirection リソース値に基づき、テキストの向きが垂直の場合にのみ適用されます"
type: docs
weight: 170
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

標準の垂直ローマン配置を取得または設定します。これは BaselineDirection リソース値に基づき、テキストの向きが垂直の場合にのみ適用されます。

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## 例

次のコードは新しい IsStandardVerticalRomanAlignmentEnabled プロパティのサポートを示しています。

```csharp
[C#]

// 次のコードは新しい IsStandardVerticalRomanAlignmentEnabled プロパティを編集できることを示しています。
// これは現在のレンダリングには影響せず、プロパティ値を編集できるようにするだけです。

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 正しい読み取り
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 正しい読み取り
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### 関連項目

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


