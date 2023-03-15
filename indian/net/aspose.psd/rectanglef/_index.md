---
title: Struct RectangleF
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.RectangleF struct. चर फ़्लटंगपइंट नंबरं क एक सेट संग्रहत करत है ज एक आयत के स्थन और आकर क प्रतनधत्व करत है
type: docs
weight: 5350
url: /hi/net/aspose.psd/rectanglef/
---
## RectangleF structure

चार फ़्लोटिंग-पॉइंट नंबरों का एक सेट संग्रहीत करता है जो एक आयत के स्थान और आकार का प्रतिनिधित्व करता है।

```csharp
public struct RectangleF
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | का एक नया उदाहरण प्रारंभ करता है`RectangleF` निर्दिष्ट स्थान और आकार के साथ संरचना. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | का एक नया उदाहरण प्रारंभ करता है`RectangleF` निर्दिष्ट स्थान और आकार के साथ संरचना. |

## गुण

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | का एक नया उदाहरण प्राप्त करता है`RectangleF` संरचना जिसमें है[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) और[`Height`](./height/) मान शून्य पर सेट. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | वाई-निर्देशांक प्राप्त या सेट करता है जो कि योग है[`Y`](./y/) और[`Height`](./height/) इस का`RectangleF`संरचना. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | इसकी ऊंचाई प्राप्त या सेट करता है`RectangleF`संरचना. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या[`Width`](./width/) या[`Height`](./height/) इस की संपत्ति`RectangleF` शून्य. का मान है |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | इसके बाएँ किनारे का x-निर्देशांक प्राप्त या सेट करता है`RectangleF`संरचना. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | इसके ऊपरी-बाएँ कोने के निर्देशांक प्राप्त या सेट करता है`RectangleF`संरचना. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | x-निर्देशांक प्राप्त करता है या सेट करता है जो कि योग है[`X`](./x/) और[`Width`](./width/) इस का`RectangleF`संरचना. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | इसका आकार प्राप्त या सेट करता है`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | इसके शीर्ष किनारे का y-निर्देशांक प्राप्त या सेट करता है`RectangleF`संरचना. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | इसकी चौड़ाई प्राप्त या सेट करता है`RectangleF`संरचना. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | इसके ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त या सेट करता है`RectangleF`संरचना. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | इसके ऊपरी-बाएँ कोने का y-निर्देशांक प्राप्त या सेट करता है`RectangleF`संरचना. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | एक बनाता है`RectangleF` निर्दिष्ट स्थानों पर ऊपरी-बाएँ कोने और निचले-दाएँ कोने के साथ संरचना। |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | एक नया बनाता है[`Rectangle`](../rectangle/) निर्दिष्ट दो बिंदुओं से। निर्मित के दो शीर्ष[`Rectangle`](../rectangle/) उत्तीर्ण के बराबर होगा*point1* और*point2* . ये विशिष्ट रूप से विपरीत शीर्ष होंगे. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | निर्दिष्ट की एक बढ़ी हुई प्रति बनाता है और लौटाता है`RectangleF`संरचना। कॉपी निर्दिष्ट राशि से फुलाया जाता है। मूल आयत अपरिवर्तित रहता है। |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | रिटर्न ए`RectangleF` संरचना जो दो आयतों के प्रतिच्छेदन का प्रतिनिधित्व करती है। यदि कोई चौराहा नहीं है, और खाली है`RectangleF` वापस आ गया है। |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | सबसे छोटा संभव तीसरा आयत बनाता है जिसमें संघ बनाने वाले दोनों आयत शामिल हो सकते हैं। |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | निर्धारित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`RectangleF`संरचना. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | निर्धारित करता है कि क्या आयताकार क्षेत्र द्वारा दर्शाया गया है*rect* इसी में पूर्णतया निहित है`RectangleF`संरचना. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | निर्धारित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`RectangleF`संरचना. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | परीक्षण करता है कि क्या*obj* एक है`RectangleF` इसके समान स्थान और आकार के साथ`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | इसके लिए हैश कोड प्राप्त करता है`RectangleF`संरचना. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | इसे फुलाता है`RectangleF`निर्दिष्ट राशि से. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | इसे फुलाता है`RectangleF` निर्दिष्ट राशि द्वारा संरचना। |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | इसे बदलता है`RectangleF`स्वयं और निर्दिष्ट के प्रतिच्छेदन के साथ संरचना`RectangleF`संरचना. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | निर्धारित करता है कि क्या यह आयत किसके साथ प्रतिच्छेद करती है*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | आयत की चौड़ाई और ऊंचाई को सकारात्मक बनाकर, बाएँ को दाएँ से कम और ऊपर को नीचे से कम बनाकर सामान्य करता है। |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | इस आयत के स्थान को निर्दिष्ट राशि से समायोजित करता है। |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | इस आयत के स्थान को निर्दिष्ट राशि से समायोजित करता है। |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | इसकी विशेषताओं को परिवर्तित करता है`RectangleF` एक मानव-पठनीय स्ट्रिंग के लिए. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | ऑपरेटर /. लागू करता है |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | परीक्षण करता है कि क्या दो हैं`RectangleF` संरचनाओं का स्थान और आकार समान होता है. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | निर्दिष्ट को परिवर्तित करता है[`Rectangle`](../rectangle/) ए के लिए संरचना`RectangleF`संरचना. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | परीक्षण करता है कि क्या दो हैं`RectangleF` संरचनाएं स्थान या आकार में भिन्न होती हैं। |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | ऑपरेटर को लागू करता है *. |

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


