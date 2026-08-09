---
title: "类 ProgressEventHandlerInfo"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo 类。此类表示图像加载/保存/导出操作的进度信息，可在外部应用程序中用于向最终用户显示转换进度。"
type: docs
weight: 5800
url: /zh/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

此类表示图像加载/保存/导出操作进度的信息，可在外部应用程序中用于向最终用户显示转换进度

```csharp
public class ProgressEventHandlerInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | 获取事件的描述 |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | 获取事件的类型。 |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | 获取上限进度值。 |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | 获取当前进度值。 |

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

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


