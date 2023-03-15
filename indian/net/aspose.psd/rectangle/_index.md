---
title: Struct Rectangle
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Rectangle struct. चर पूर्णंकं क एक सेट संग्रहत करत है ज एक आयत के स्थन और आकर क प्रतनधत्व करत है
type: docs
weight: 5340
url: /hi/net/aspose.psd/rectangle/
---
## Rectangle structure

चार पूर्णांकों का एक सेट संग्रहीत करता है जो एक आयत के स्थान और आकार का प्रतिनिधित्व करता है।

```csharp
public struct Rectangle
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | का एक नया उदाहरण प्रारंभ करता है`Rectangle` निर्दिष्ट स्थान और आकार के साथ संरचना. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | का एक नया उदाहरण प्रारंभ करता है`Rectangle` निर्दिष्ट स्थान और आकार के साथ संरचना. |

## गुण

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | का एक नया उदाहरण प्राप्त करता है`Rectangle` संरचना जिसमें है[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) और[`Height`](./height/) मान शून्य पर सेट. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | वाई-निर्देशांक प्राप्त करता है या सेट करता है जो कि योग है[`Y`](./y/) और[`Height`](./height/) इस के संपत्ति मूल्य`Rectangle`संरचना. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | इसकी ऊंचाई प्राप्त या सेट करता है`Rectangle`संरचना. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इसके सभी संख्यात्मक गुण हैं`Rectangle` शून्य के मान हैं। |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | इसके बाएँ किनारे का x-निर्देशांक प्राप्त या सेट करता है`Rectangle`संरचना. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | इसके ऊपरी-बाएँ कोने के निर्देशांक प्राप्त या सेट करता है`Rectangle`संरचना. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | x-निर्देशांक प्राप्त करता है या सेट करता है जो कि योग है[`X`](./x/) और[`Width`](./width/) इस के संपत्ति मूल्य`Rectangle`संरचना. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | इसका आकार प्राप्त या सेट करता है`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | इसके शीर्ष किनारे का y-निर्देशांक प्राप्त या सेट करता है`Rectangle`संरचना. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | इसकी चौड़ाई प्राप्त या सेट करता है`Rectangle`संरचना. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | इसके ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त या सेट करता है`Rectangle`संरचना. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | इसके ऊपरी-बाएँ कोने का y-निर्देशांक प्राप्त या सेट करता है`Rectangle`संरचना. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | निर्दिष्ट को परिवर्तित करता है[`RectangleF`](../rectanglef/) ए के लिए संरचना`Rectangle` गोल करके संरचना[`RectangleF`](../rectanglef/) अगले उच्च पूर्णांक मानों के लिए मान. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | एक बनाता है`Rectangle` निर्दिष्ट बढ़त स्थानों के साथ संरचना. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | एक नया बनाता है`Rectangle` निर्दिष्ट दो बिंदुओं से। निर्मित के दो कार्यक्षेत्र`Rectangle` उत्तीर्ण के बराबर होगा*point1* और*point2* . ये विशिष्ट रूप से विपरीत शीर्ष होंगे. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | निर्दिष्ट की एक बढ़ी हुई प्रति बनाता है और लौटाता है`Rectangle`संरचना। कॉपी निर्दिष्ट राशि से फुलाया जाता है। मूल`Rectangle` संरचना अपरिवर्तित बनी हुई है। |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | एक तिहाई लौटाता है`Rectangle` संरचना जो दो अन्य के प्रतिच्छेदन का प्रतिनिधित्व करती है`Rectangle` संरचनाएं। यदि कोई चौराहा नहीं है, तो एक खाली`Rectangle` वापस आ गया है। |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | निर्दिष्ट को परिवर्तित करता है[`RectangleF`](../rectanglef/) एक के लिए`Rectangle` गोल करके[`RectangleF`](../rectanglef/) मानों को निकटतम पूर्णांक मान. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | निर्दिष्ट को परिवर्तित करता है[`RectangleF`](../rectanglef/) एक के लिए`Rectangle` काट कर[`RectangleF`](../rectanglef/) मान. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | हो जाता है`Rectangle` संरचना जिसमें दो का मिलन होता है`Rectangle` संरचनाएं. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | निर्धारित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`Rectangle`संरचना. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | निर्धारित करता है कि क्या आयताकार क्षेत्र द्वारा दर्शाया गया है*rect* इसी में पूर्णतया निहित है`Rectangle`संरचना. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | निर्धारित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`Rectangle`संरचना. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | परीक्षण करता है कि क्या*obj* एक है`Rectangle`इस के समान स्थान और आकार के साथ संरचना`Rectangle`संरचना. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | इसके लिए हैश कोड लौटाता है`Rectangle`संरचना. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | इसे फुलाता है`Rectangle`निर्दिष्ट राशि से. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | इसे फुलाता है`Rectangle`निर्दिष्ट राशि से. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | इसे बदलता है`Rectangle` स्वयं और निर्दिष्ट के प्रतिच्छेदन के साथ`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | निर्धारित करता है कि क्या यह आयत किसके साथ प्रतिच्छेद करती है*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | आयत की चौड़ाई और ऊंचाई को सकारात्मक बनाकर, बाएँ को दाएँ से कम और ऊपर को नीचे से कम बनाकर सामान्य करता है। |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | इस आयत के स्थान को निर्दिष्ट राशि से समायोजित करता है। |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | इस आयत के स्थान को निर्दिष्ट राशि से समायोजित करता है। |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | इसकी विशेषताओं को परिवर्तित करता है`Rectangle` एक मानव-पठनीय स्ट्रिंग के लिए. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | परीक्षण करता है कि क्या दो हैं`Rectangle` संरचनाओं का स्थान और आकार समान होता है. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | परीक्षण करता है कि क्या दो हैं`Rectangle` संरचनाएं स्थान या आकार में भिन्न होती हैं। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


