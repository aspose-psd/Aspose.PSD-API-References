---
title: StreamSource.StreamSource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: StreamSource नर्मत. क एक नय उदहरण प्ररंभ करत हैStreamSource वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`StreamSource`](../) वर्ग.

```csharp
public StreamSource(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | खोलने के लिए धारा। |

### उदाहरण

यह उदाहरण दिखाता है कि कैसे पिक्सेल जानकारी को प्रकार के रंग की एक सरणी में लोड किया जाता है, सरणी में हेरफेर किया जाता है और इसे छवि पर वापस सेट किया जाता है। इन कार्यों को करने के लिए, यह उदाहरण मेमोरीस्ट्रीम ऑब्जेक्ट का उपयोग करके एक नई छवि फ़ाइल (PSD प्रारूप में) बनाता है।

```csharp
[C#]

// मेमोरीस्ट्रीम का एक उदाहरण बनाएं
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // PsdOptions का एक उदाहरण बनाएं और स्रोत गुण सहित इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    // छवि का एक उदाहरण बनाएं
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // क्षेत्र को छवि सीमा के रूप में निर्दिष्ट करके छवि के पिक्सेल प्राप्त करें
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // ऐरे पर लूप करें और एलरेनेटिव इंडेक्स्ड पिक्सेल का रंग सेट करें
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // अनुक्रमित पिक्सेल रंग को पीले रंग में सेट करें
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                // अनुक्रमित पिक्सेल रंग को नीले रंग में सेट करें
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // छवि में पिक्सेल परिवर्तन लागू करें
        image.SavePixels(image.Bounds, pixels);

        // सभी परिवर्तनों को सहेजें।
        image.Save();
    }

    // फ़ाइल में मेमोरीस्ट्रीम लिखें
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### यह सभी देखें

* class [StreamSource](../)
* नाम स्थान [Aspose.PSD.Sources](../../streamsource/)
* सभा [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`StreamSource`](../) वर्ग.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | खोलने के लिए धारा। |
| disposeStream | Boolean | अगर सेट है`सत्य` धारा का निस्तारण किया जाएगा। |

### उदाहरण

यह उदाहरण एक नई छवि फ़ाइल बनाने के लिए System.IO.Stream के उपयोग को प्रदर्शित करता है

```csharp
[C#]

// PsdOptions का एक उदाहरण बनाता है और इसके विभिन्न गुणों को सेट करता है
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// System.IO.Stream का एक उदाहरण बनाएँ
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

// PsdOptions के उदाहरण के लिए स्रोत संपत्ति को परिभाषित करें
// दूसरा बूलियन पैरामीटर निर्धारित करता है कि क्या एक बार दायरे से बाहर हो जाने पर स्ट्रीम का निपटान किया जाता है
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// इमेज का एक उदाहरण बनाता है और इमेज ऑब्जेक्ट को इनिशियलाइज़ करने के लिए पैरामीटर के रूप में PsdOptions के साथ क्रिएट मेथड को कॉल करता है   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // कुछ इमेज प्रोसेसिंग करें
}
```

### यह सभी देखें

* class [StreamSource](../)
* नाम स्थान [Aspose.PSD.Sources](../../streamsource/)
* सभा [Aspose.PSD](../../../)


