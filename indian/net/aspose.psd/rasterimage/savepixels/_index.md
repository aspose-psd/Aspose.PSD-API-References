---
title: "RasterImage.SavePixels"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RasterImage मेथड। पिक्सेल सहेजता है।"
type: docs
weight: 540
url: /hi/net/aspose.psd/rasterimage/savepixels/
---
{{< psd/tize >}}
## RasterImage.SavePixels method

पिक्सेल को सहेजता है।

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| आयत | Rectangle | पिक्सेल सहेजने के लिए आयत। |
| पिक्सेल | Color[] | पिक्सेल एरे। |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


