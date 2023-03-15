---
title: TextFontInfo.Style
second_title: Aspose.PSD for .NET API 参考
description: TextFontInfo 财产. 获取从子家族名称 解析的字体样式
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

获取从子家族名称 解析的字体样式

```csharp
public FontStyle Style { get; }
```

### 适当的价值

从子家族名称 解析的字体样式

### 例子

下面的代码演示了 Aspose.PSD 如何获取文本层内联格式的属性。

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

        // 获取包含在文本层中的字体
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

### 也可以看看

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* 部件 [Aspose.PSD](../../../)


