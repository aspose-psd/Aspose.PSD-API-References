---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD for .NET API リファレンス
description: Txt2Resource 方法. テキスト レコードをリソースに追加しテキスト レコードの ID を返します
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

テキスト レコードをリソースに追加し、テキスト レコードの ID を返します。

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| text | String | レコードのテキスト。 |
| bounds | RectangleF | 境界。 |

### 戻り値

resource のテキスト レコードの ID を返します

### 例外

| 例外 | 調子 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Txt2 リソースのバージョンが不明です。 |

### 例

次のコードは、新しい ITextStyle プロパティのサポートのサポートを示しています。

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string srcFile = "A.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    var textLayer = (TextLayer)psdImage.Layers[1];
    textLayer.UpdateText("abc");

    psdImage.Save(outputFile);
}

// 値をチェック
using (var srcImage = (PsdImage)Image.Load(srcFile))
{
    var srcTextLayer = (TextLayer)srcImage.Layers[1];
    var etalonStyle = srcTextLayer.TextData.Items[0].Style;

    using (var outImage = (PsdImage)Image.Load(outputFile))
    {
        var outTextLayer = (TextLayer)outImage.Layers[1];
        var resultStyle = outTextLayer.TextData.Items[0].Style;

        AssertAreEqual(etalonStyle.AutoLeading, resultStyle.AutoLeading);
        AssertAreEqual(etalonStyle.FontIndex, resultStyle.FontIndex);
        AssertAreEqual(etalonStyle.Underline, resultStyle.Underline);
        AssertAreEqual(etalonStyle.Strikethrough, resultStyle.Strikethrough);
        AssertAreEqual(etalonStyle.AutoKerning, resultStyle.AutoKerning);
        AssertAreEqual(etalonStyle.StandardLigatures, resultStyle.StandardLigatures);
        AssertAreEqual(etalonStyle.DiscretionaryLigatures, resultStyle.DiscretionaryLigatures);
        AssertAreEqual(etalonStyle.ContextualAlternates, resultStyle.ContextualAlternates);
        AssertAreEqual(etalonStyle.LanguageIndex, resultStyle.LanguageIndex);
        AssertAreEqual(etalonStyle.VerticalScale, resultStyle.VerticalScale);
        AssertAreEqual(etalonStyle.HorizontalScale, resultStyle.HorizontalScale);
        AssertAreEqual(etalonStyle.Fractions, resultStyle.Fractions);
    }
}
```

### 関連項目

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* 組み立て [Aspose.PSD](../../../)


