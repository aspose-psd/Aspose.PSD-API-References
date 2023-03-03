---
title: RasterCachedImage.RotateFlip
second_title: .NET API 참조용 Aspose.PSD
description: RasterCachedImage 방법. 이미지를 회전 뒤집기 또는 회전하고 뒤집습니다.
type: docs
weight: 140
url: /ko/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

이미지를 회전, 뒤집기 또는 회전하고 뒤집습니다.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 회전 뒤집기 유형입니다. |

### 예

다음 코드는 이미지를 회전하는 방법을 보여줍니다.

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

### 또한보십시오

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* 네임스페이스 [Aspose.PSD](../../rastercachedimage/)
* 집회 [Aspose.PSD](../../../)


