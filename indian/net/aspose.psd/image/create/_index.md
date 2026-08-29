---
title: "Image.Create"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Image मेथड। निर्दिष्ट क्रिएट विकल्पों का उपयोग करके नई इमेज बनाता है"
type: docs
weight: 10
url: /hi/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई इमेज बनाता है।

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | इमेज विकल्प। |
| चौड़ाई | Int32 | चौड़ाई। |
| ऊँचाई | Int32 | ऊँचाई। |

### रिटर्न वैल्यू

नव निर्मित इमेज।

## उदाहरण

यह उदाहरण PsdOptions इंस्टेंस की Source प्रॉपर्टी द्वारा निर्दिष्ट डिस्क स्थान पर एक नई Image फ़ाइल बनाता है। वास्तविक इमेज बनाने से पहले PsdOptions इंस्टेंस की कई प्रॉपर्टी सेट की जाती हैं। विशेष रूप से Source प्रॉपर्टी, जो इस मामले में वास्तविक डिस्क स्थान को दर्शाती है।

```csharp
[C#]

//PsdOptions का एक इंस्टेंस बनाएँ और उसकी विभिन्न प्रॉपर्टी सेट करें।
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource का एक इंस्टेंस बनाएँ और उसे PsdOptions इंस्टेंस के लिए Source के रूप में असाइन करें।
//दूसरा Boolean पैरामीटर निर्धारित करता है कि बनाई जाने वाली फ़ाइल अस्थायी है या नहीं।
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image का एक इंस्टेंस बनाएँ और Create मेथड को कॉल करके उसे PsdOptions के इंस्टेंस से इनिशियलाइज़ करें।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //कुछ छवि प्रसंस्करण करें।

    // सभी परिवर्तन सहेजें।
    image.Save();
}
```

### देखें भी

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


