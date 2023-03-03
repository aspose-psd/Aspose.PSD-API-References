---
title: Class Font
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Font कक्ष. फन्ट फेस आकर और शैल वशेषतओं सहत पठ के लए एक वशेष प्ररूप क परभषत करत है इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 4280
url: /hi/net/aspose.psd/font/
---
## Font class

फॉन्ट फेस, आकार और शैली विशेषताओं सहित पाठ के लिए एक विशेष प्रारूप को परिभाषित करता है। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class Font
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | एक नया आरंभ करता है`Font` जो निर्दिष्ट मौजूदा का उपयोग करता है`Font` और[`FontStyle`](../fontstyle/) गणना. |
| [Font](font/#constructor_1)(string, float) | एक नया आरंभ करता है`Font` एक निर्दिष्ट आकार का उपयोग करना। वर्ण सेट पर सेट हैDefault , ग्राफिक्स यूनिट कोPoint , फ़ॉन्ट शैली toRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | एक नया आरंभ करता है`Font` एक निर्दिष्ट आकार और शैली का उपयोग करना। वर्ण सेट पर सेट हैDefault , ग्राफिक्स यूनिट कोPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | एक नया आरंभ करता है`Font` एक निर्दिष्ट आकार और इकाई का उपयोग करना। वर्ण सेट पर सेट हैDefault शैली पर सेट हैRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | एक नया आरंभ करता है`Font` एक निर्दिष्ट आकार, शैली और इकाई का उपयोग करना। |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | एक नया आरंभ करता है`Font` एक निर्दिष्ट आकार, शैली, इकाई और वर्ण सेट का उपयोग करना। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह`Font` बोल्ड है. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | एक बाइट मान प्राप्त करता है जो वर्ण सेट को निर्दिष्ट करता है कि यह`Font` उपयोग करता है. |
| [Italic](../../aspose.psd/font/italic/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह`Font`इटैलिक है. |
| [Name](../../aspose.psd/font/name/) { get; } | इसके चेहरे का नाम प्राप्त करता है`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | इसका एम-साइज़ प्राप्त करता है`Font` द्वारा निर्दिष्ट इकाइयों में मापा जाता है[`Unit`](./unit/) संपत्ति. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह`Font` फ़ॉन्ट के माध्यम से एक क्षैतिज रेखा निर्दिष्ट करता है। |
| [Style](../../aspose.psd/font/style/) { get; } | इसके लिए स्टाइल की जानकारी प्राप्त करता है`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह`Font` रेखांकित किया गया है। |
| [Unit](../../aspose.psd/font/unit/) { get; } | इसके लिए माप की इकाई प्राप्त करता है`Font` . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | इसकी सटीक डीप कॉपी बनाता है`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | इंगित करता है कि निर्दिष्ट वस्तु एक है या नहीं`Font` और इसके समान गुण मान हैं`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | इसके लिए हैश कोड प्राप्त करता है`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | इसका एक मानव-पठनीय स्ट्रिंग प्रतिनिधित्व देता है`Font` . |

### उदाहरण

यह उदाहरण छवि सतह पर तार खींचने के लिए फ़ॉन्ट और सॉलिडब्रश वर्ग के उपयोग को प्रदर्शित करता है। उदाहरण एक नई छवि बनाता है और आंकड़े और ग्राफिक्सपाथ का उपयोग करके आकृतियाँ बनाता है

```csharp
[C#]

// छवि का एक उदाहरण बनाता है
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स वर्ग का एक उदाहरण बनाता है और आरंभ करता है
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // ग्राफिक्स की सतह को साफ करता है
    graphics.Clear(Color.Wheat);

    // फ़ॉन्ट का एक उदाहरण बनाता है
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // लाल रंग वाले सॉलिडब्रश का एक उदाहरण बनाएं
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // एक स्ट्रिंग ड्रा करें
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // निर्यात विकल्प बनाएँ।
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // सभी परिवर्तनों को सहेजें
    image.Save("C:\\temp\\output.gif", options);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


