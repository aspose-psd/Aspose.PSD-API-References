---
title: "स्ट्रक्ट RectangleF"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.RectangleF स्ट्रक्ट। चार फ्लोटिंग पॉइंट संख्याओं का सेट संग्रहीत करता है जो आयत की स्थिति और आकार को दर्शाते हैं।"
type: docs
weight: 5850
url: /hi/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

एक आयत के स्थान और आकार का प्रतिनिधित्व करने वाले चार फ्लोटिंग-पॉइंट संख्याओं का सेट संग्रहीत करता है।

```csharp
public struct RectangleF
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | `RectangleF` संरचना का नया उदाहरण निर्दिष्ट स्थिति और आकार के साथ आरंभ करता है। |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | `RectangleF` संरचना का नया उदाहरण निर्दिष्ट स्थिति और आकार के साथ आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | `RectangleF` संरचना का नया उदाहरण प्राप्त करता है जिसमें [`X`](./x/), [`Y`](./y/), [`Width`](./width/) और [`Height`](./height/) मान शून्य पर सेट होते हैं। |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | इस `RectangleF` संरचना के y-निर्देशांक को प्राप्त करता है या सेट करता है, जो [`Y`](./y/) और [`Height`](./height/) का योग है। |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | इस `RectangleF` संरचना की ऊँचाई को प्राप्त करता है या सेट करता है। |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि इस `RectangleF` की [`Width`](./width/) या [`Height`](./height/) गुण का मान शून्य है या नहीं। |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | इस `RectangleF` संरचना के बाएँ किनारे के x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | इस `RectangleF` संरचना के ऊपर-बाएँ कोने के निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | इस `RectangleF` संरचना के x-निर्देशांक को प्राप्त करता है या सेट करता है, जो [`X`](./x/) और [`Width`](./width/) का योग है। |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | इस `RectangleF` का आकार प्राप्त करता है या सेट करता है। |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | इस `RectangleF` संरचना के शीर्ष किनारे के y-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | इस `RectangleF` संरचना की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | इस `RectangleF` संरचना के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | इस `RectangleF` संरचना के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | निर्दिष्ट स्थानों पर ऊपर-बाएँ और नीचे-दाएँ कोनों के साथ एक `RectangleF` संरचना बनाता है। |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | निर्दिष्ट दो बिंदुओं से एक नया [`Rectangle`](../rectangle/) बनाता है। बनाए गए [`Rectangle`](../rectangle/) के दो शीर्ष बिंदु पास किए गए *point1* और *point2* के बराबर होंगे। ये सामान्यतः विपरीत शीर्ष बिंदु होते हैं। |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | निर्दिष्ट `RectangleF` संरचना की एक फुलायी हुई प्रति बनाता है और लौटाता है। प्रति निर्दिष्ट मात्रा से फुलायी जाती है। मूल आयत अपरिवर्तित रहती है। |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | दो आयतों के प्रतिच्छेदन को दर्शाने वाली एक `RectangleF` संरचना लौटाता है। यदि कोई प्रतिच्छेदन नहीं है, तो एक खाली `RectangleF` लौटाई जाती है। |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | दो आयतों के संघ को सम्मिलित करने वाला सबसे छोटा संभव तृतीय आयत बनाता है। |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | निर्दिष्ट बिंदु इस `RectangleF` संरचना के भीतर स्थित है या नहीं निर्धारित करता है। |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | यह निर्धारित करता है कि *rect* द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस `RectangleF` संरचना के भीतर स्थित है या नहीं। |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | निर्दिष्ट बिंदु इस `RectangleF` संरचना के भीतर स्थित है या नहीं निर्धारित करता है। |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | जाँचता है कि *obj* इस `RectangleF` के समान स्थान और आकार वाला `RectangleF` है या नहीं। |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | इस `RectangleF` संरचना के लिए हैश कोड प्राप्त करता है। |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | इस `RectangleF` को निर्दिष्ट मात्रा से फुलाता है। |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | इस `RectangleF` संरचना को निर्दिष्ट मात्रा से फुलाता है। |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | इस `RectangleF` संरचना को स्वयं और निर्दिष्ट `RectangleF` संरचना के प्रतिच्छेदन से बदलता है। |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | निर्धारित करता है कि यह आयत *rect* के साथ प्रतिच्छेद करती है या नहीं। |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | आयत को सामान्यीकृत करता है, जिससे इसकी चौड़ाई और ऊँचाई सकारात्मक हो जाती है, बायाँ दाएँ से कम और शीर्ष नीचे से कम हो जाता है। |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | निर्दिष्ट मात्रा द्वारा इस आयत का स्थान समायोजित करता है। |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | निर्दिष्ट मात्रा द्वारा इस आयत का स्थान समायोजित करता है। |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | इस `RectangleF` के गुणों को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| [operator /](../../aspose.psd/rectanglef/op_division/) | ऑपरेटर / को लागू करता है। |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | जाँचता है कि दो `RectangleF` संरचनाओं का स्थान और आकार समान है या नहीं। |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | निर्दिष्ट [`Rectangle`](../rectangle/) संरचना को `RectangleF` संरचना में परिवर्तित करता है। |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | जाँचता है कि दो `RectangleF` संरचनाओं का स्थान या आकार अलग है या नहीं। |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | ऑपरेटर * को लागू करता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


