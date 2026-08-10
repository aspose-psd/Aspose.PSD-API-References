---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "StreamSource कंस्ट्रक्टर। StreamSource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

[`StreamSource`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public StreamSource(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | खोलने के लिए स्ट्रीम। |

## उदाहरण

यह उदाहरण दिखाता है कि कैसे पिक्सेल जानकारी को Color प्रकार की एरे में लोड किया जाता है, एरे को संशोधित किया जाता है और उसे इमेज में वापस सेट किया जाता है। इन ऑपरेशनों को करने के लिए, यह उदाहरण MemoryStream ऑब्जेक्ट का उपयोग करके एक नई Image फ़ाइल (PSD फ़ॉर्मेट में) बनाता है।

```csharp
[C#]

//MemoryStream का एक इंस्टेंस बनाएँ।
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions का एक इंस्टेंस बनाएँ और उसकी विभिन्न प्रॉपर्टी, जिसमें Source प्रॉपर्टी भी शामिल है, सेट करें।
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image का एक इंस्टेंस बनाएँ।
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //छवि की सीमा को निर्दिष्ट करके छवि के पिक्सेल प्राप्त करें
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //ऐरे पर लूप करें और वैकल्पिक अनुक्रमित पिक्सेल का रंग सेट करें
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //अनुक्रमित पिक्सेल का रंग पीला सेट करें
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //अनुक्रमित पिक्सेल का रंग नीला सेट करें
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //पिक्सेल परिवर्तन को छवि पर लागू करें
        image.SavePixels(image.Bounds, pixels);

        // सभी परिवर्तन सहेजें।
        image.Save();
    }

    //MemoryStream को फ़ाइल में लिखें
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### देखें भी

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

[`StreamSource`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | खोलने के लिए स्ट्रीम। |
| disposeStream | बूलियन | `true` पर सेट करने पर स्ट्रीम डिस्पोज़ हो जाएगी। |

## उदाहरण

यह उदाहरण System.IO.Stream के उपयोग को दर्शाता है जिससे नई छवि फ़ाइल बनाई जाती है।

```csharp
[C#]

//PsdOptions का एक इंस्टेंस बनाता है और उसकी विभिन्न प्रॉपर्टीज़ सेट करता है।
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream का एक इंस्टेंस बनाएं।
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions के इंस्टेंस के लिए स्रोत प्रॉपर्टी को परिभाषित करें।
//दूसरा बूलियन पैरामीटर निर्धारित करता है कि क्या Stream को स्कोप से बाहर निकलते ही डिस्पोज़ किया जाता है।
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image का एक इंस्टेंस बनाता है और Image ऑब्जेक्ट को प्रारंभ करने के लिए PsdOptions को पैरामीटर के रूप में देकर Create मेथड को कॉल करता है।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //कुछ छवि प्रसंस्करण करें।
}
```

### देखें भी

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


