---
title: "Enum AutoKerning"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.AutoKerning enum. Photoshop の自動カーニングモード（シンボル間の距離）"
type: docs
weight: 1610
url: /ja/net/aspose.psd.fileformats.psd/autokerning/
---
{{< psd/tize >}}
## AutoKerning enumeration

Photoshop の自動カーニングモード（シンボル間の距離）。

```csharp
public enum AutoKerning
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Manual | `0` | 手動カーニング値。 |
| Metric | `1` | メトリックカーニングは、ほとんどのフォントに含まれるカーンペア（デザイナー提供）を使用します。 |
| Optical | `2` | 光学カーニングは、隣接文字の形状に基づいて間隔を調整します。 |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


