---
title: "TextLayer.GetFonts"
second_title: "Aspose.PSD for .NET API 参考"
description: "TextLayer 方法。获取文本图层的字体集合"
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
{{< psd/tize >}}
## TextLayer.GetFonts method

获取文本图层的字体集合。

```csharp
public TextFontInfo[] GetFonts()
```

### 返回值

文本图层的字体集合。

## 示例

以下代码演示了 Aspose.PSD 如何获取文本图层内联格式的属性。

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// 将现有图像加载到 PsdImage 类的实例中
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // 获取文本图层中包含的字体
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### 另请参阅

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


