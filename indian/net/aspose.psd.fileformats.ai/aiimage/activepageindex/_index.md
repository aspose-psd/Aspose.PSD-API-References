---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "AiImage प्रॉपर्टी। सक्रिय पृष्ठ का इंडेक्स प्राप्त करता है या सेट करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

सक्रिय पेज का इंडेक्स प्राप्त करता है या सेट करता है।

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

यह प्रॉपर्टी केवल PDF फ़ॉर्मेट AI इमेज के लिए लागू है। यदि इमेज PDF फ़ॉर्मेट में नहीं है या कोई पृष्ठ नहीं हैं, तो प्रॉपर्टी -1 होगी। यह प्रॉपर्टी दर्शाती है कि AI इमेज का कौन सा पृष्ठ रेंडरिंग के लिए आधार होगा।

## उदाहरण

निम्नलिखित कोड AI इमेज में सक्रिय पृष्ठ बदलने की क्षमता के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// AI इमेज लोड करें।
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // डिफ़ॉल्ट रूप से, ActivePageIndex 0 है।
    // इसलिए यदि आप इस प्रॉपर्टी को बदले बिना AI इमेज को सहेजते हैं, तो पहला पृष्ठ रेंडर होकर सहेजा जाएगा।
    image.Save(firstPageOutputPng, new PngOptions());

    // सक्रिय पृष्ठ इंडेक्स को दूसरे पृष्ठ पर बदलें।
    image.ActivePageIndex = 1;

    // AI इमेज के दूसरे पृष्ठ को PNG इमेज के रूप में सहेजें।
    image.Save(secondPageOutputPng, new PngOptions());

    // सक्रिय पृष्ठ इंडेक्स को तीसरे पृष्ठ पर बदलें।
    image.ActivePageIndex = 2;

    // AI इमेज के तीसरे पृष्ठ को PNG इमेज के रूप में सहेजें।
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### देखें भी

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


