---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage method. छवि को केंद्र के चारों ओर घुमाता है"
type: docs
weight: 670
url: /hi/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

इमेज को केंद्र के चारों ओर घुमाता है।

```csharp
public override void Rotate(float angle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कोण | Single | घुमाव का कोण डिग्री में। सकारात्मक मान घड़ी की दिशा में घुमाएंगे। |

## उदाहरण

निम्नलिखित कोड यह दर्शाता है कि कैसे छवि को विशिष्ट कोण मान से घुमाया जा सकता है।

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// पूरी छवि का घुमाव
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// लेयर का घुमाव
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### देखें भी

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

इमेज को केंद्र के चारों ओर घुमाता है।

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कोण | Single | घुमाव का कोण डिग्री में। सकारात्मक मान घड़ी की दिशा में घुमाएंगे। |
| resizeProportionally | बूलियन | यदि `true` सेट किया जाता है तो आपका इमेज आकार घुमाए गए आयत (कोर्नर पॉइंट्स) के प्रोजेक्शन के अनुसार बदल जाएगा, अन्यथा आयाम अपरिवर्तित रहेंगे और केवल आंतरिक इमेज सामग्री घुमाई जाएगी। |
| backgroundColor | रंग | पृष्ठभूमि का रंग। |

### देखें भी

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


