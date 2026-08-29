---
title: "संरचना Rectangle"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Rectangle संरचना। चार पूर्णांकों का सेट संग्रहीत करता है जो एक आयत के स्थान और आकार का प्रतिनिधित्व करते हैं।"
type: docs
weight: 5840
url: /hi/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

एक आयत के स्थान और आकार को दर्शाने वाले चार पूर्णांकों का सेट संग्रहीत करता है।

```csharp
public struct Rectangle
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | निर्दिष्ट स्थान और आकार के साथ `Rectangle` संरचना का नया उदाहरण आरंभ करता है। |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | निर्दिष्ट स्थान और आकार के साथ `Rectangle` संरचना का नया उदाहरण आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | एक नया `Rectangle` संरचना का उदाहरण प्राप्त करता है जिसमें [`X`](./x/), [`Y`](./y/), [`Width`](./width/) और [`Height`](./height/) मान शून्य पर सेट होते हैं। |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | इस `Rectangle` संरचना के [`Y`](./y/) और [`Height`](./height/) गुण मानों के योग वाले y-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | इस `Rectangle` संरचना की ऊँचाई को प्राप्त करता है या सेट करता है। |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि इस `Rectangle` की सभी संख्यात्मक गुणों के मान शून्य हैं या नहीं। |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | इस `Rectangle` संरचना के बाएँ किनारे के x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | इस `Rectangle` संरचना के ऊपर-बाएँ कोने के निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | इस `Rectangle` संरचना के [`X`](./x/) और [`Width`](./width/) गुण मानों के योग वाले x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | इस `Rectangle` का आकार प्राप्त करता है या सेट करता है। |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | इस `Rectangle` संरचना के शीर्ष किनारे के y-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | इस `Rectangle` संरचना की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | इस `Rectangle` संरचना के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | इस `Rectangle` संरचना के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना को `Rectangle` संरचना में बदलता है, जहाँ [`RectangleF`](../rectanglef/) मानों को अगले बड़े पूर्णांक मान तक गोल किया जाता है। |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | निर्दिष्ट किनारे के स्थानों के साथ एक `Rectangle` संरचना बनाता है। |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | निर्दिष्ट दो बिंदुओं से एक नया `Rectangle` बनाता है। बनाए गए `Rectangle` की दो ऊर्ध्वाधर रेखाएँ पास किए गए *point1* और *point2* के बराबर होंगी। ये सामान्यतः विपरीत शीर्ष बिंदु होते हैं। |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | निर्दिष्ट `Rectangle` संरचना की एक फुलायी हुई प्रति बनाता है और लौटाता है। प्रति को निर्दिष्ट मात्रा से फुलाया जाता है। मूल `Rectangle` संरचना अपरिवर्तित रहती है। |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | दो अन्य `Rectangle` संरचनाओं के प्रतिच्छेदन को दर्शाने वाली तीसरी `Rectangle` संरचना लौटाता है। यदि कोई प्रतिच्छेदन नहीं है, तो एक खाली `Rectangle` लौटाया जाता है। |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | निर्दिष्ट [`RectangleF`](../rectanglef/) को `Rectangle` में बदलता है, जहाँ [`RectangleF`](../rectanglef/) मानों को निकटतम पूर्णांक मान तक गोल किया जाता है। |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | निर्दिष्ट [`RectangleF`](../rectanglef/) को `Rectangle` में बदलता है, जहाँ [`RectangleF`](../rectanglef/) मानों को काटकर पूर्णांक बनाया जाता है। |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | दो `Rectangle` संरचनाओं के संघ को सम्मिलित करने वाली एक `Rectangle` संरचना प्राप्त करता है। |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | निर्दिष्ट बिंदु इस `Rectangle` संरचना के भीतर स्थित है या नहीं निर्धारित करता है। |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | निर्धारित करता है कि *rect* द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस `Rectangle` संरचना के भीतर स्थित है या नहीं। |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | निर्दिष्ट बिंदु इस `Rectangle` संरचना के भीतर स्थित है या नहीं निर्धारित करता है। |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | जाँचता है कि *obj* इस `Rectangle` संरचना के समान स्थान और आकार वाला `Rectangle` संरचना है या नहीं। |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | इस `Rectangle` संरचना के लिए हैश कोड लौटाता है। |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | इस `Rectangle` को निर्दिष्ट मात्रा से फुलाता है। |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | इस `Rectangle` को निर्दिष्ट मात्रा से फुलाता है। |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | इस `Rectangle` को स्वयं और निर्दिष्ट `Rectangle` के प्रतिच्छेदन से बदलता है। |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | निर्धारित करता है कि यह आयत *rect* के साथ प्रतिच्छेद करती है या नहीं। |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | आयत को सामान्यीकृत करता है, जिससे इसकी चौड़ाई और ऊँचाई सकारात्मक हो जाती है, बायाँ दाएँ से कम और शीर्ष नीचे से कम हो जाता है। |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | निर्दिष्ट मात्रा द्वारा इस आयत का स्थान समायोजित करता है। |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | निर्दिष्ट मात्रा द्वारा इस आयत का स्थान समायोजित करता है। |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | इस `Rectangle` के गुणों को मानव-पठनीय स्ट्रिंग में बदलता है। |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | जाँचता है कि दो `Rectangle` संरचनाओं का स्थान और आकार समान है या नहीं। |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | जाँचता है कि दो `Rectangle` संरचनाओं का स्थान या आकार अलग है या नहीं। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


