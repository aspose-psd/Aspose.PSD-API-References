---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD for .NET API 参考
description: Txt2Resource 方法. 将文本记录添加到 Resource 并返回文本记录的 id
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

将文本记录添加到 Resource 并返回文本记录的 id。

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 记录文本。 |
| bounds | RectangleF | 界限。 |

### 返回值

返回 resource 文本记录的 ID

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 未知的 Txt2 资源版本。 |

### 例子

以下代码演示了对新 ITextStyle 属性的支持。

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

// 检查值
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

### 也可以看看

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* 部件 [Aspose.PSD](../../../)


