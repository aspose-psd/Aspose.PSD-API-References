---
title: ImageOptionsBase.DefaultReplacementFont
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ImageOptionsBase संपत्त. डफ़ल्ट प्रतस्थपन फ़न्ट प्रप्त करत है य सेट करत है फ़न्ट ज रेखपुंज में नर्यत करते समय पठ क आकर्षत करने के लए उपयग कय जएग यद PSD फ़इल में मजूद परत फ़न्ट सस्टम में प्रस्तुत नहं कय गय है डफ़ल्ट फ़न्ट क उचत नम लेने के लए अगले कड स्नपेट क उपयग कय ज सकत है  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily family  col.Families string defaultFontName  family0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /hi/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रेखापुंज में निर्यात करते समय पाठ को आकर्षित करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा परत फ़ॉन्ट सिस्टम में प्रस्तुत नहीं किया गया है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम लेने के लिए अगले कोड स्निपेट का उपयोग किया जा सकता है : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### संपत्ति मूल्य

डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट।

### उदाहरण

निम्न उदाहरण दिखाता है कि डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट को बदलने के लिए DefaultReplacementFont गुण का उपयोग कैसे करें।

```csharp
[C#]

// कृपया, कॉन्स्टेंटिंग फ़ॉन्ट इंस्टॉल न करें, क्योंकि इस परीक्षण को उस फ़ॉन्ट को प्रतिस्थापित करना चाहिए जो इंस्टॉल नहीं है
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // इस तरह आप अलग-अलग आउटपुट के लिए अलग-अलग फॉन्ट का इस्तेमाल कर सकते हैं 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### यह सभी देखें

* class [ImageOptionsBase](../)
* नाम स्थान [Aspose.PSD](../../imageoptionsbase/)
* सभा [Aspose.PSD](../../../)


