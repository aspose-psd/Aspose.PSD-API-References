---
title: RasterImage.Crop
second_title: Aspose.PSD for .NET API 参考
description: RasterImage 方法. 裁剪指定的矩形
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

以下代码示例显示如何裁剪图像并保存它。

```csharp
[C#]

// 为 PSD 文件实施正确的 Crop 方法。
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

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* 命名空间 [Aspose.PSD](../../rasterimage/)
* 部件 [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

带位移的裁剪图像。

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | Int32 | 左移。 |
| rightShift | Int32 | 正确的转变。 |
| topShift | Int32 | 上移。 |
| bottomShift | Int32 | 下移。 |

### 也可以看看

* class [RasterImage](../)
* 命名空间 [Aspose.PSD](../../rasterimage/)
* 部件 [Aspose.PSD](../../../)


