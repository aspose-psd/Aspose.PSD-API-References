---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD for .NET API 参考
description: ITextStyle 财产. 获取或设置标准垂直罗马对齐方式 这基于 BaselineDirection 资源值仅适用于文本方向为Vertical .
type: docs
weight: 170
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

获取或设置标准垂直罗马对齐方式。 这基于 BaselineDirection 资源值仅适用于文本方向为Vertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### 例子

以下代码演示了对新的 IsStandardVerticalRomanAlignmentEnabled 属性的支持。

```csharp
[C#]

// 以下代码演示了编辑新的 IsStandardVerticalRomanAlignmentEnabled 属性的能力。
// 这暂时不影响渲染，但只允许您编辑属性值。

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 正确读法
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
        // 正确读法
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### 也可以看看

* interface [ITextStyle](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* 部件 [Aspose.PSD](../../../)


