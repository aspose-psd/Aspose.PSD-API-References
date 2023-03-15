---
title: Enum AutoKerning
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.AutoKerning 列挙. Photoshop 自動カーニング モード シンボル間の距離.
type: docs
weight: 1600
url: /ja/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

Photoshop 自動カーニング モード (シンボル間の距離).

```csharp
public enum AutoKerning
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Manual | `0` | 手動カーニング値. |
| Metric | `1` | メトリクス カーニングは、ほとんどのフォントに含まれているカーニング ペアを使用します (デザイナーによる)。 |
| Optical | `2` | オプティカル カーニングは、形状に基づいて隣接する文字間の間隔を調整します。 |

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

* 名前空間 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 組み立て [Aspose.PSD](../../)


