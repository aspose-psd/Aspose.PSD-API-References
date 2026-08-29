---
title: "类 PsdLoadOptions"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions 类。Psd 加载选项"
type: docs
weight: 5250
url: /zh/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

PSD 加载选项

```csharp
public class PsdLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | 获取或设置在渲染期间是否在图层未被修改时保留原始图层像素。 |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | 获取或设置是否使用渲染图像保存，是否带有或不带有扭曲变换。 |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | 获取或设置 [`Image`](../../aspose.psd/image/) 背景 [`Color`](../../aspose.psd/color/)。 |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | 获取或设置数据恢复模式。 |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | 获取或设置一个值，指示是否 [ignore alpha channel]。 |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | 获取或设置一个值，指示在执行 UpdateText 操作时是否忽略 PSD 文本图层的固定宽度。 |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | 获取或设置一个值，指示是否 [load effects resource]（默认情况下资源未加载）。设置此选项后，仅支持的效果将渲染到最终合并图像。 |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | 获取或设置一个值，指示是否 [use read only mode]。这是只读模式，支持与 Adobe Photoshop 完全兼容。当此选项被设置时，对图层所做的所有更改将不会保存到最终图像。所有数据均来自 ImageData 部分，因此与 Photoshop 完全相同。默认情况下，所有加载的图像都不完全兼容 Adobe Photoshop。 |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | 获取或设置加载 PSD 图像时使用的只读模式。 |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | 获取或设置一个值，指示是否 [use disk for load effects resource]（默认使用磁盘加载效果资源，但如果将此值设为 false，则可以使用足够的内存）。 |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | 获取或设置一个值，指示是否应应用 ICC 配置文件转换。 |

## 示例

以下示例演示文档转换进度正常工作且没有异常。

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### 另请参阅

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


