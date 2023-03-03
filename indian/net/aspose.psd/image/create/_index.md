---
title: Image.Create
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Image तरक. नर्दष्ट नर्मण वकल्पं क उपयग करके एक नई छव बनत है
type: docs
weight: 10
url: /hi/net/aspose.psd/image/create/
---
## Image.Create method

निर्दिष्ट निर्माण विकल्पों का उपयोग करके एक नई छवि बनाता है।

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | छवि विकल्प। |
| width | Int32 | चौड़ाई. |
| height | Int32 | ऊंचाई. |

### प्रतिलाभ की मात्रा

नई बनाई गई छवि।

### उदाहरण

यह उदाहरण PsdOptions उदाहरण के स्रोत गुण द्वारा निर्दिष्ट डिस्क स्थान पर एक नई छवि फ़ाइल बनाता है। वास्तविक छवि बनाने से पहले PsdOptions उदाहरण के लिए कई गुण सेट किए गए हैं। विशेष रूप से स्रोत संपत्ति, जो इस मामले में वास्तविक डिस्क स्थान को संदर्भित करती है।

```csharp
[C#]

// PsdOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource का एक उदाहरण बनाएं और इसे PsdOptions के उदाहरण के लिए स्रोत के रूप में असाइन करें
// दूसरा बूलियन पैरामीटर निर्धारित करता है कि बनाई जाने वाली फ़ाइल टेम्पोरल है या नहीं
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// इमेज का एक उदाहरण बनाएं और क्रिएट मेथड को कॉल करके PsdOptions के उदाहरण के साथ इसे इनिशियलाइज़ करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // कुछ इमेज प्रोसेसिंग करें

    // सभी परिवर्तनों को सहेजें
    image.Save();
}
```

### यह सभी देखें

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)


