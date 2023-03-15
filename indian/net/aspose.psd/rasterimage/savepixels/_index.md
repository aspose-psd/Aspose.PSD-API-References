---
title: RasterImage.SavePixels
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: RasterImage तरक. पक्सेल सहेजत है.
type: docs
weight: 520
url: /hi/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

पिक्सेल सहेजता है.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | Rectangle | वह आयत जिसमें पिक्सेल सहेजना है। |
| pixels | Color[] | पिक्सेल सरणी। |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* नाम स्थान [Aspose.PSD](../../rasterimage/)
* सभा [Aspose.PSD](../../../)


