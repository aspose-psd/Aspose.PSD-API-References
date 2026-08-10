---
title: "क्लास Font"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Font क्लास। टेक्स्ट के लिए एक विशिष्ट फ़ॉर्मेट को परिभाषित करता है जिसमें फ़ॉन्ट फ़ेस आकार और शैली गुण शामिल हैं। इस क्लास को विरासत में नहीं लिया जा सकता।"
type: docs
weight: 4750
url: /hi/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

पाठ के लिए एक विशिष्ट फ़ॉर्मेट को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं। इस क्लास को विरासत में नहीं लिया जा सकता।

```csharp
public sealed class Font
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | एक नया `Font` आरंभ करता है जो निर्दिष्ट मौजूदा `Font` और [`FontStyle`](../fontstyle/) एनोमरेशन का उपयोग करता है। |
| [Font](font/#constructor_1)(string, float) | एक नया `Font` निर्दिष्ट आकार का उपयोग करके आरंभ करता है। कैरेक्टर सेट को Default पर, ग्राफ़िक्स यूनिट को Point पर, फ़ॉन्ट शैली को Regular पर सेट किया जाता है। |
| [Font](font/#constructor_2)(string, float, FontStyle) | एक नया `Font` निर्दिष्ट आकार और शैली का उपयोग करके आरंभ करता है। कैरेक्टर सेट को Default पर, ग्राफ़िक्स यूनिट को Point पर सेट किया जाता है। |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | एक नया `Font` निर्दिष्ट आकार और इकाई का उपयोग करके आरंभ करता है। कैरेक्टर सेट को Default पर, शैली को Regular पर सेट किया जाता है। |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | एक नया `Font` निर्दिष्ट आकार, शैली और इकाई का उपयोग करके आरंभ करता है। |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | निर्दिष्ट आकार, शैली, इकाई और अक्षर सेट का उपयोग करके एक नया `Font` प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह `Font` बोल्ड है या नहीं। |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | एक बाइट मान प्राप्त करता है जो इस `Font` द्वारा उपयोग किए जाने वाले अक्षर सेट को निर्दिष्ट करता है। |
| [Italic](../../aspose.psd/font/italic/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह `Font` इटैलिक है या नहीं। |
| [Name](../../aspose.psd/font/name/) { get; } | इस `Font` का फ़ेस नाम प्राप्त करता है। |
| [Size](../../aspose.psd/font/size/) { get; } | इस `Font` का इम-साइज़ प्राप्त करता है, जो [`Unit`](./unit/) प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में मापा जाता है। |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह `Font` फ़ॉन्ट के माध्यम से एक क्षैतिज रेखा निर्दिष्ट करता है या नहीं। |
| [Style](../../aspose.psd/font/style/) { get; } | इस `Font` के लिए शैली जानकारी प्राप्त करता है। |
| [Underline](../../aspose.psd/font/underline/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह `Font` अंडरलाइन है या नहीं। |
| [Unit](../../aspose.psd/font/unit/) { get; } | इस `Font` के लिए माप इकाई प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | इस `Font` की एक सटीक डीप कॉपी बनाता है। |
| override [Equals](../../aspose.psd/font/equals/)(object) | यह संकेत देता है कि निर्दिष्ट ऑब्जेक्ट एक `Font` है और इस `Font` के समान प्रॉपर्टी मान रखता है। |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | इस `Font` के लिए हैश कोड प्राप्त करता है। |
| override [ToString](../../aspose.psd/font/tostring/)() | इस `Font` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

## उदाहरण

यह उदाहरण फ़ॉन्ट और SolidBrush क्लास का उपयोग करके इमेज सतह पर स्ट्रिंग्स ड्रॉ करने को दर्शाता है। उदाहरण एक नई इमेज बनाता है और फ़िगर्स तथा GraphicsPath का उपयोग करके आकार ड्रॉ करता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाता है
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाता है और इनिशियलाइज़ करता है
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करता है
    graphics.Clear(Color.Wheat);

    //Font का एक इंस्टेंस बनाता है
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //लाल रंग वाला SolidBrush का एक इंस्टेंस बनाता है
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //एक स्ट्रिंग ड्रॉ करता है
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // एक्सपोर्ट विकल्प बनाता है।
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.gif", options);
}
```

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


