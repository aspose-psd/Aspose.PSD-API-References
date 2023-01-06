---
title: Crop
second_title: Aspose.PSD for .NET API 参考
description: 裁剪指定的矩形
type: docs
weight: 240
url: /zh/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

裁剪指定的矩形。

```csharp
public virtual void Crop(Rectangle rectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 矩形。 |

### 例子

以下代码示例显示了如何裁剪图像并保存它。

```csharp
[C#]

// 为 PSD 文件实现正确的裁剪方法。
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 也可以看看

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.PSD](../../rasterimage)
* 部件 [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

使用班次裁剪图像。

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | Int32 | 左移。 |
| rightShift | Int32 | 右移。 |
| topShift | Int32 | 最高班次。 |
| bottomShift | Int32 | 下移。 |

### 也可以看看

* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.PSD](../../rasterimage)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->