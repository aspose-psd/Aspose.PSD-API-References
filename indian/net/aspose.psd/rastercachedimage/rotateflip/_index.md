---
title: RasterCachedImage.RotateFlip
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: RasterCachedImage तरक. छव क घुमत है फ़्लप करत है य घुमत है और फ़्लप करत है.
type: docs
weight: 140
url: /hi/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | रोटेट फ्लिप प्रकार। |

### उदाहरण

निम्न कोड दिखाता है कि छवि को कैसे घुमाएं।

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

### यह सभी देखें

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* नाम स्थान [Aspose.PSD](../../rastercachedimage/)
* सभा [Aspose.PSD](../../../)


