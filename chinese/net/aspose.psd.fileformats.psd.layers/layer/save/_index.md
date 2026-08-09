---
title: "Layer.Save"
second_title: "Aspose.PSD for .NET API 参考"
description: "Layer 方法。将对象数据保存到指定的流"
type: docs
weight: 390
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

将对象的数据保存到指定的流。

```csharp
public override void Save(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 用于保存对象数据的流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 我们不应该在没有 Image 选项的情况下调用 Save 方法 |

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| 选项 | ImageOptionsBase | 选项。 |

### 另请参阅

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

将对象的数据保存到指定的文件位置。

```csharp
public override void Save(string filePath, bool overWrite)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 用于保存对象数据的文件路径。 |
| overWrite | 布尔 | 如果设置为 `true`，则覆盖文件内容，否则将进行追加。 |

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 用于保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。设置空矩形以使用源边界。 |

### 另请参阅

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| 选项 | ImageOptionsBase | 选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。设置空矩形以使用源边界。 |

### 另请参阅

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


