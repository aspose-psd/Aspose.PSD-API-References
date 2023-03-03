---
title: PsdImage.Rotate
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage तरक. इमेज क बच में घुमएं.
type: docs
weight: 610
url: /hi/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

इमेज को बीच में घुमाएं.

```csharp
public override void Rotate(float angle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | Single | घूर्णन कोण डिग्री में। धनात्मक मान दक्षिणावर्त घूमेंगे। |

### उदाहरण

निम्न कोड विशिष्ट कोण मान द्वारा छवि को घुमाने की क्षमता प्रदर्शित करता है।

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// पूरी छवि घूम रही है
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

// परत घूम रही है
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

### यह सभी देखें

* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

इमेज को बीच में घुमाएं.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | Single | घूर्णन कोण डिग्री में। धनात्मक मान दक्षिणावर्त घूमेंगे। |
| resizeProportionally | Boolean | अगर सेट है`सत्य` घुमाए गए आयत (कोने के बिंदु) अनुमानों के अनुसार आपकी छवि का आकार बदल जाएगा, अन्य मामले में जो आयामों को अछूता छोड़ देता है और केवल आंतरिक छवि सामग्री घुमाई जाती है। |
| backgroundColor | Color | पृष्ठभूमि का रंग। |

### यह सभी देखें

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


