---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdOptions 属性。获取或设置背景颜色。它可以在透明对象下看到。"
type: docs
weight: 20
url: /zh/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

获取或设置背景颜色。它可在透明对象下看到。

```csharp
public RawColor BackgroundContents { get; set; }
```

## 示例

以下代码演示了在 PsdOptions 中对 BackgroundContents 属性的支持。

```csharp
[C#]

// 在 PSD 文件预览中，半透明处理错误。
// BackgroundContents 被分配为白色。透明区域应为白色。

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### 另请参阅

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


