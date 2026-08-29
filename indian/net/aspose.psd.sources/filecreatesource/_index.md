---
title: "क्लास FileCreateSource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Sources.FileCreateSource क्लास। निर्माण के लिए फ़ाइल स्रोत का प्रतिनिधित्व करता है"
type: docs
weight: 6090
url: /hi/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

निर्माण के लिए फ़ाइल स्रोत को दर्शाता है।

```csharp
public sealed class FileCreateSource : FileSource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | `FileCreateSource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | `FileCreateSource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | निर्माण के लिए फ़ाइल पथ प्राप्त करता है। |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | फ़ाइल अस्थायी होगी या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | स्ट्रीम कंटेनर प्राप्त करता है। |

## उदाहरण

यह उदाहरण फ़ॉन्ट और SolidBrush क्लास का उपयोग करके इमेज सतह पर स्ट्रिंग्स ड्रॉ करने को दर्शाता है। उदाहरण एक नई इमेज बनाता है और फ़िगर्स तथा GraphicsPath का उपयोग करके आकार ड्रॉ करता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाता है
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाता है और इनिशियलाइज़ करता है
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करता है
    graphics.Clear(Color.Wheat);

    //Font का एक इंस्टेंस बनाता है
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //लाल रंग वाला SolidBrush का एक इंस्टेंस बनाता है
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //एक स्ट्रिंग ड्रॉ करता है
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // एक्सपोर्ट विकल्प बनाता है।
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.gif", options);
}
```

### देखें भी

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


