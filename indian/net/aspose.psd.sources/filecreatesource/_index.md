---
title: Class FileCreateSource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Sources.FileCreateSource कक्ष. नर्मण के लए फ़इल स्रत क प्रतनधत्व करत है
type: docs
weight: 5590
url: /hi/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

निर्माण के लिए फ़ाइल स्रोत का प्रतिनिधित्व करता है।

```csharp
public sealed class FileCreateSource : FileSource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | का एक नया उदाहरण प्रारंभ करता है`FileCreateSource` वर्ग. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | का एक नया उदाहरण प्रारंभ करता है`FileCreateSource` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | बनाने के लिए फ़ाइल पथ प्राप्त करता है. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि फ़ाइल अस्थायी होगी या नहीं। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | स्ट्रीम कंटेनर प्राप्त करता है। |

### उदाहरण

यह उदाहरण छवि सतह पर तार खींचने के लिए फ़ॉन्ट और सॉलिडब्रश वर्ग के उपयोग को प्रदर्शित करता है। उदाहरण एक नई छवि बनाता है और आंकड़े और ग्राफिक्सपाथ का उपयोग करके आकृतियाँ बनाता है

```csharp
[C#]

// छवि का एक उदाहरण बनाता है
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स वर्ग का एक उदाहरण बनाता है और आरंभ करता है
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // ग्राफिक्स की सतह को साफ करता है
    graphics.Clear(Color.Wheat);

    // फ़ॉन्ट का एक उदाहरण बनाता है
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // लाल रंग वाले सॉलिडब्रश का एक उदाहरण बनाएं
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // एक स्ट्रिंग ड्रा करें
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // निर्यात विकल्प बनाएँ।
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // सभी परिवर्तनों को सहेजें
    image.Save("C:\\temp\\output.gif", options);
}
```

### यह सभी देखें

* class [FileSource](../filesource/)
* नाम स्थान [Aspose.PSD.Sources](../../aspose.psd.sources/)
* सभा [Aspose.PSD](../../)


