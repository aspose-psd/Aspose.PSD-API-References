---
title: "Image.RotateFlip"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Image मेथड। इमेज को घुमाता, फ्लिप करता या घुमाकर फ्लिप करता है"
type: docs
weight: 230
url: /hi/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

इमेज को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है।

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | रोटेट फ़्लिप का प्रकार। |

## उदाहरण

यह उदाहरण इमेज पर Rotate ऑपरेशन के उपयोग को दर्शाता है। उदाहरण कुछ डिस्क स्थान से मौजूदा इमेज फ़ाइल लोड करता है और Enum Aspose.PSD.RotateFlipType के मान के अनुसार इमेज पर Rotate ऑपरेशन लागू करता है

```csharp
[C#]

//image क्लास की एक इंस्टेंस बनाएं और फ़ाइल पाथ के माध्यम से मौजूदा इमेज फ़ाइल से इसे इनिशियलाइज़ करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //इमेज को X अक्ष के बारे में 180 डिग्री घुमाएँ
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // सभी परिवर्तन सहेजें।
    image.Save();
}
```

### देखें भी

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


