---
title: Image.Resize
second_title: Aspose.PSD for .NET API 参考
description: Image 方法. 调整图像大小
type: docs
weight: 190
url: /zh/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

调整图像大小。

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新宽度. |
| newHeight | Int32 | 新高度. |
| resizeType | ResizeType | 调整大小类型。 |

### 也可以看看

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* 命名空间 [Aspose.PSD](../../image/)
* 部件 [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

调整图像大小。默认值LeftTopToLeftTop使用.

```csharp
public void Resize(int newWidth, int newHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新宽度. |
| newHeight | Int32 | 新高度. |

### 例子

以下示例演示如何调整 PSD 图像的大小以及我们通过 Aspose.PSD 获得的结果

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 也可以看看

* class [Image](../)
* 命名空间 [Aspose.PSD](../../image/)
* 部件 [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

调整图像大小。

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| settings | ImageResizeSettings | 调整大小设置。 |

### 也可以看看

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* 命名空间 [Aspose.PSD](../../image/)
* 部件 [Aspose.PSD](../../../)


