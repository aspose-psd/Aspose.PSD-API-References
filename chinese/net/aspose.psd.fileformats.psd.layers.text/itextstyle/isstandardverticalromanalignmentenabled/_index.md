---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD for .NET API 参考"
description: "ITextStyle 属性。获取或设置标准垂直罗马对齐方式。此基于 BaselineDirection 资源值，仅在文本方向为垂直时适用"
type: docs
weight: 170
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

获取或设置标准垂直罗马对齐方式。此基于 BaselineDirection 资源值的设置仅在文本方向为垂直时适用。

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## 示例

以下代码演示了对新 IsStandardVerticalRomanAlignmentEnabled 属性的支持。

```csharp
[C#]

// 以下代码演示了编辑新 IsStandardVerticalRomanAlignmentEnabled 属性的能力。
// 这目前不会影响渲染，但仅允许您编辑属性值。

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // 正确读取
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
        // 正确读取
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### 另请参阅

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


