---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD for .NET API リファレンス
description: RasterCachedImage 方法. 画像を回転反転または回転して反転します
type: docs
weight: 140
url: /ja/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

画像を回転、反転、または回転して反転します。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 回転フリップタイプ。 |

### 例

次のコードは、画像を回転する方法を示しています。

```csharp
[C#]

var sourceFile = "1.psd";
var pngPath = "RotateFlipTest2617.png";
var psdPath = "RotateFlipTest2617.psd";
var flipType = RotateFlipType.Rotate270FlipXY;
using (var im = (PsdImage)(Image.Load(sourceFile)))
{
    im.RotateFlip(flipType);
    im.Save(pngPath, new PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
    im.Save(psdPath);
}
```

### 関連項目

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* 名前空間 [Aspose.PSD](../../rastercachedimage/)
* 組み立て [Aspose.PSD](../../../)


