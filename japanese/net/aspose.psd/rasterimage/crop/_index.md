---
title: RasterImage.Crop
second_title: Aspose.PSD for .NET API リファレンス
description: RasterImage 方法. 指定された長方形をトリミングします
type: docs
weight: 240
url: /ja/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

指定された長方形をトリミングします。

```csharp
public virtual void Crop(Rectangle rectangle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rectangle | Rectangle | 長方形。 |

### 例

次のコード例は、画像をトリミングして保存する方法を示しています。

```csharp
[C#]

// PSD ファイルの正しい Crop メソッドを実装します。
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
* 名前空間 [Aspose.PSD](../../rasterimage/)
* 組み立て [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

シフトで画像をトリミングします。

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| leftShift | Int32 | 左シフト。 |
| rightShift | Int32 | 右シフト。 |
| topShift | Int32 | トップシフト。 |
| bottomShift | Int32 | ボトムシフト。 |

### 関連項目

* class [RasterImage](../)
* 名前空間 [Aspose.PSD](../../rasterimage/)
* 組み立て [Aspose.PSD](../../../)


