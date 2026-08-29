---
title: "ImageAttributes.SetRemapTable"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageAttributes 方法。设置默认类别的 colorremap 表。"
type: docs
weight: 190
url: /zh/net/aspose.psd/imageattributes/setremaptable/
---
{{< psd/tize >}}
## SetRemapTable(ColorMap[]) {#setremaptable}

为默认类别设置颜色重新映射表。

```csharp
public void SetRemapTable(ColorMap[] map)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| map | ColorMap[] | 类型为 [`ColorMap`](../../colormap/) 的颜色对数组。每个颜色对包含一个现有颜色（第一个值）和它将被映射到的颜色（第二个值）。 |

### 另请参阅

* class [ColorMap](../../colormap/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetRemapTable(ColorMap[], ColorAdjustType) {#setremaptable_1}

为指定类别设置颜色重新映射表。

```csharp
public void SetRemapTable(ColorMap[] map, ColorAdjustType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| map | ColorMap[] | 类型为 [`ColorMap`](../../colormap/) 的颜色对数组。每个颜色对包含一个现有颜色（第一个值）和它将被映射到的颜色（第二个值）。 |
| type | ColorAdjustType | [`ColorAdjustType`](../../coloradjusttype/) 的一个元素，指定设置 color-remap 表的类别。 |

### 另请参阅

* class [ColorMap](../../colormap/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


