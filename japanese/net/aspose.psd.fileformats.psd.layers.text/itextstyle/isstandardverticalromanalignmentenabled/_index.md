---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD for .NET API リファレンス
description: ITextStyle 財産. 標準の垂直ローマン配置を取得または設定します これは BaselineDirection リソース値に基づいておりテキストの向きがVertical .
type: docs
weight: 170
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

標準の垂直ローマン配置を取得または設定します。 これは BaselineDirection リソース値に基づいており、テキストの向きがVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### 例

次のコードは、新しい IsStandardVerticalRomanAlignmentEnabled プロパティのサポートを示しています。

```csharp
[C#]

// 次のコードは、新しい IsStandardVerticalRomanAlignmentEnabled プロパティを編集する機能を示しています。
// これは現時点ではレンダリングには影響しませんが、プロパティ値の編集のみ可能です。

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 正しい読み方
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
        // 正しい読み方
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### 関連項目

* interface [ITextStyle](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* 組み立て [Aspose.PSD](../../../)


