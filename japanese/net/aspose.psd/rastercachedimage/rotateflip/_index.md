---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.PSD for .NET API Reference"
description: "RasterCachedImage メソッド。画像を回転・反転、または回転と反転を行います"
type: docs
weight: 140
url: /ja/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

画像を回転、フリップ、または回転とフリップを行います。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 回転・反転のタイプです。 |

## 例

以下のコードは画像の回転方法を示しています。

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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


