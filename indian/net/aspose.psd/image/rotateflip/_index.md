---
title: Image.RotateFlip
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Image तरक. छव क घुमत है फ़्लप करत है य घुमत है और फ़्लप करत है.
type: docs
weight: 220
url: /hi/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | रोटेट फ्लिप का प्रकार। |

### उदाहरण

यह उदाहरण एक इमेज पर रोटेट ऑपरेशन के उपयोग को प्रदर्शित करता है। उदाहरण किसी डिस्क स्थान से एक मौजूदा छवि फ़ाइल को लोड करता है और Enum Aspose.PSD.RotateFlipType के मान के अनुसार छवि पर घुमाएँ कार्रवाई करता है

```csharp
[C#]

// छवि वर्ग का एक उदाहरण बनाएं और इसे फ़ाइल पथ के माध्यम से मौजूदा छवि फ़ाइल के साथ प्रारंभ करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // एक्स अक्ष के बारे में छवि को 180 डिग्री पर घुमाएं
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // सभी परिवर्तनों को सहेजें।
    image.Save();
}
```

### यह सभी देखें

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)


