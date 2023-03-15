---
title: Layer.Save
second_title: Aspose.PSD for .NET API 参考
description: Layer 方法. 将对象的数据保存到指定的流中
type: docs
weight: 370
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/save/
---
## Save(Stream) {#save_1}

将对象的数据保存到指定的流中。

```csharp
public override void Save(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 将对象数据保存到的流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 我们不应该在没有图像选项的情况下调用 Save 方法 |

### 也可以看看

* class [Layer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 部件 [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |

### 也可以看看

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 部件 [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

将对象的数据保存到指定的文件位置。

```csharp
public override void Save(string filePath, bool overWrite)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 保存对象数据的文件路径。 |
| overWrite | Boolean | 如果设置为`真的`覆盖文件内容，否则会发生追加。 |

### 也可以看看

* class [Layer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 部件 [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

根据保存选项以指定文件格式将图像数据保存到指定流。

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 将图像数据保存到的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。设置空矩形以使用源边界。 |

### 也可以看看

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 部件 [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

根据保存选项以指定的文件格式将对象的数据保存到指定的文件位置。

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| options | ImageOptionsBase | 选项。 |
| boundsRectangle | Rectangle | 目标图像边界矩形。设置空矩形以使用源边界。 |

### 也可以看看

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* 部件 [Aspose.PSD](../../../)


