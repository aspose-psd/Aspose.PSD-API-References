---
title: "RasterImage.Crop"
second_title: "Aspose.PSD for .NET API Reference"
description: "RasterImage メソッド。指定された矩形で画像を切り取ります"
type: docs
weight: 240
url: /ja/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

指定された矩形を切り取ります。

```csharp
public virtual void Crop(Rectangle rectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形です。 |

## 例

以下のコード例は、画像を切り取って保存する方法を示しています。

```csharp
[C#]

// PSD ファイル用に正しい Crop メソッドを実装してください。
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

### 関連項目

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

シフト付きで画像をトリミングします。

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| leftShift | Int32 | 左シフトです。 |
| rightShift | Int32 | 右シフトです。 |
| topShift | Int32 | 上シフトです。 |
| bottomShift | Int32 | 下シフトです。 |

### 関連項目

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


