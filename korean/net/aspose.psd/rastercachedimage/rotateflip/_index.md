---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "RasterCachedImage 메서드. 이미지를 회전 뒤집거나 회전 및 뒤집기를 수행합니다"
type: docs
weight: 140
url: /ko/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 회전 뒤집기 유형. |

## 예제

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

### 또 보기

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


