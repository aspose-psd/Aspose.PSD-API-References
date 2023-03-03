---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD لمرجع .NET API
description: RasterCachedImage طريقة. يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها.
type: docs
weight: 140
url: /ar/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | نوع تدوير الوجه. |

### أمثلة

يوضح الكود التالي كيفية تدوير الصورة.

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

### أنظر أيضا

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* مساحة الاسم [Aspose.PSD](../../rastercachedimage/)
* المجسم [Aspose.PSD](../../../)


