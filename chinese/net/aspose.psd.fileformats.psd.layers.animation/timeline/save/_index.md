---
title: "Timeline.Save"
second_title: "Aspose.PSD for .NET API 参考"
description: "Timeline 方法。根据保存选项，将 PsdImages 和 Timeline 数据保存到指定文件位置的指定格式。"
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

根据保存选项，将 PsdImage 和 Timeline 数据保存到指定文件位置的指定格式中。

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| 选项 | ImageOptionsBase | 选项。 |

## 示例

以下代码演示了将 Timeline 导出为 Gif 图像的支持。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### 另请参阅

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

根据保存选项，将 PsdImage 和 Timeline 数据保存到指定流的指定格式中。

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | 流 | 输出流。 |
| 选项 | ImageOptionsBase | 选项。 |

## 示例

以下代码演示了将 Timeline 导出为 Gif 图像的支持。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### 另请参阅

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


