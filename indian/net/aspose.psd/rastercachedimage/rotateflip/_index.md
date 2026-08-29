---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RasterCachedImage मेथड। इमेज को घुमाता, फ़्लिप करता या घुमाता और फ़्लिप करता है"
type: docs
weight: 140
url: /hi/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

इमेज को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है।

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | रोटेट फ़्लिप प्रकार। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि इमेज को कैसे घुमाया जाए।

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

### देखें भी

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


