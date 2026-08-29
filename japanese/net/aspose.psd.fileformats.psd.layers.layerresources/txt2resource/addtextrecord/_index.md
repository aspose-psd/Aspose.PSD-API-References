---
title: "Txt2Resource.AddTextRecord"
second_title: "Aspose.PSD for .NET API Reference"
description: "Txt2Resource メソッド。テキストレコードをリソースに追加し、テキストレコードの ID を返します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
{{< psd/tize >}}
## Txt2Resource.AddTextRecord method

テキストレコードをリソースに追加し、テキストレコードの ID を返します。

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | 文字列 | レコードテキストです。 |
| bounds | RectangleF | 境界です。 |

### 戻り値

リソースのテキストレコードのIDを返します

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 不明な Txt2 リソース バージョンです。 |

## 例

次のコードは、新しい ITextStyle プロパティのサポートを示します。

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

// 値を確認する
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


