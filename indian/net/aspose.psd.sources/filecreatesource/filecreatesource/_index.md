---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FileCreateSource कन्स्ट्रक्टर। FileCreateSource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

[`FileCreateSource`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public FileCreateSource(string filePath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | निर्माण के लिए फ़ाइल पथ। |

## उदाहरण

यह उदाहरण BmpOptions इंस्टेंस की Source प्रॉपर्टी द्वारा निर्दिष्ट डिस्क स्थान पर एक नई Image फ़ाइल बनाता है। यदि FileCreateSource के कन्स्ट्रक्टर को दूसरा पैरामीटर नहीं दिया जाता है, तो डिफ़ॉल्ट रूप से बनाई जाने वाली फ़ाइल की IsTemporal प्रॉपर्टी True पर सेट होती है। जब IsTemporal True पर सेट हो, तो निष्पादन के अंत में कोई फ़ाइल डिस्क पर सहेजी नहीं जाएगी।

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//PsdOptions का एक इंस्टेंस बनाता है और उसकी विभिन्न प्रॉपर्टीज़ सेट करता है।
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource का एक इंस्टेंस बनाएँ और उसे PsdOptions इंस्टेंस के लिए Source के रूप में असाइन करें।
//यदि दूसरा पैरामीटर नहीं दिया जाता है, तो डिफ़ॉल्ट रूप से फ़ाइल की IsTemporal True पर सेट होती है।
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Image का एक इंस्टेंस बनाता है।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //कुछ छवि प्रसंस्करण करें।
}
```

### देखें भी

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

[`FileCreateSource`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | निर्माण के लिए फ़ाइल पथ। |
| isTemporal | बूलियन | यदि `true` पर सेट किया जाता है, तो बनाई गई फ़ाइल अस्थायी होगी। |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


