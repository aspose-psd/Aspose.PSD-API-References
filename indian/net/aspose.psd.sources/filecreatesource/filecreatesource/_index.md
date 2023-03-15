---
title: FileCreateSource.FileCreateSource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FileCreateSource नर्मत. क एक नय उदहरण प्ररंभ करत हैFileCreateSource वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`FileCreateSource`](../) वर्ग.

```csharp
public FileCreateSource(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | बनाने के लिए फ़ाइल पथ। |

### उदाहरण

यह उदाहरण BmpOptions उदाहरण के स्रोत गुण द्वारा निर्दिष्ट डिस्क स्थान पर एक नई छवि फ़ाइल बनाता है। यदि दूसरा पैरामीटर FileCreateSource के कंस्ट्रक्टर को पास नहीं किया गया है, तो डिफ़ॉल्ट रूप से बनाई जाने वाली फ़ाइल में संपत्ति IsTemporal True पर सेट है। IsTemporal को True पर सेट करने के साथ, निष्पादन के अंत में डिस्क पर कोई फ़ाइल सहेजी नहीं जाएगी।

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
// PsdOptions का एक उदाहरण बनाता है और इसके विभिन्न गुणों को सेट करता है
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource का एक उदाहरण बनाएं और इसे PsdOptions के उदाहरण के लिए स्रोत के रूप में असाइन करें
// यदि दूसरा पैरामीटर पास नहीं हुआ है, तो डिफ़ॉल्ट रूप से फ़ाइल में IsTemporal को True पर सेट किया गया है
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

// छवि का एक उदाहरण बनाता है 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // कुछ इमेज प्रोसेसिंग करें
}
```

### यह सभी देखें

* class [FileCreateSource](../)
* नाम स्थान [Aspose.PSD.Sources](../../filecreatesource/)
* सभा [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`FileCreateSource`](../) वर्ग.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | बनाने के लिए फ़ाइल पथ। |
| isTemporal | Boolean | अगर सेट है`सत्य` बनाई गई फ़ाइल अस्थायी होगी। |

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

* class [FileCreateSource](../)
* नाम स्थान [Aspose.PSD.Sources](../../filecreatesource/)
* सभा [Aspose.PSD](../../../)


