---
title: "स्ट्रक्ट Point"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Point स्ट्रक्ट। यह पूर्णांक x और ycoordinates की क्रमबद्ध जोड़ी का प्रतिनिधित्व करता है जो द्वि-आयामी तल में एक बिंदु को परिभाषित करती है।"
type: docs
weight: 5760
url: /hi/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

दो-आयामी तल में बिंदु को परिभाषित करने वाले पूर्णांक x और y निर्देशांक की क्रमबद्ध जोड़ी का प्रतिनिधित्व करता है।

```csharp
public struct Point
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Point](point/#constructor_1)(int) | `Point` संरचना का नया उदाहरण इनिशियलाइज़ करता है जो पूर्णांक मान द्वारा निर्दिष्ट निर्देशांक का उपयोग करता है। |
| [Point](point/#constructor)(Size) | `Point` संरचना का नया उदाहरण इनिशियलाइज़ करता है [`Size`](../size/) संरचना से। |
| [Point](point/#constructor_2)(int, int) | `Point` संरचना का नया उदाहरण निर्दिष्ट निर्देशांक के साथ इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | `Point` संरचना का नया उदाहरण प्राप्त करता है जिसकी [`X`](./x/) और [`Y`](./y/) मान शून्य पर सेट हैं। |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | यह `Point` खाली है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [X](../../aspose.psd/point/x/) { get; set; } | इस `Point` का x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [Y](../../aspose.psd/point/y/) { get; set; } | इस `Point` का y-निर्देशांक प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | निर्दिष्ट [`Size`](../size/) को निर्दिष्ट `Point` में जोड़ता है। |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | निर्दिष्ट [`PointF`](../pointf/) को `Point` में परिवर्तित करता है, [`PointF`](../pointf/) के मानों को अगले उच्च पूर्णांक मान तक गोल करके। |
| static [Round](../../aspose.psd/point/round/)(PointF) | निर्दिष्ट [`PointF`](../pointf/) को `Point` ऑब्जेक्ट में परिवर्तित करता है, `Point` मानों को निकटतम पूर्णांक तक गोल करके। |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | निर्दिष्ट `Point` से निर्दिष्ट [`Size`](../size/) घटाने का परिणाम लौटाता है। |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | निर्दिष्ट [`PointF`](../pointf/) को `Point` में परिवर्तित करता है, `Point` के मानों को ट्रंकेट करके। |
| override [Equals](../../aspose.psd/point/equals/)(object) | निर्दिष्ट ऑब्जेक्ट के समान निर्देशांक इस `Point` में हैं या नहीं, यह निर्दिष्ट करता है। |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | इस `Point` के लिए हैश कोड लौटाता है। |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | इस `Point` को निर्दिष्ट `Point` द्वारा ट्रांसलेट करता है। |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | इस `Point` को निर्दिष्ट मात्रा द्वारा ट्रांसलेट करता है। |
| override [ToString](../../aspose.psd/point/tostring/)() | इस `Point` को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| [operator +](../../aspose.psd/point/op_addition/) | `Point` को दिए गए [`Size`](../size/) द्वारा ट्रांसलेट करता है। |
| [operator ==](../../aspose.psd/point/op_equality/) | दो `Point` ऑब्जेक्ट्स की तुलना करता है। परिणाम यह निर्दिष्ट करता है कि दो `Point` ऑब्जेक्ट्स की [`X`](./x/) और [`Y`](./y/) प्रॉपर्टीज़ के मान समान हैं या नहीं। |
| [explicit operator](../../aspose.psd/point/op_explicit/) | निर्दिष्ट `Point` स्ट्रक्चर को एक [`Size`](../size/) स्ट्रक्चर में परिवर्तित करता है। |
| [implicit operator](../../aspose.psd/point/op_implicit/) | निर्दिष्ट `Point` स्ट्रक्चर को [`PointF`](../pointf/) स्ट्रक्चर में परिवर्तित करता है। |
| [operator !=](../../aspose.psd/point/op_inequality/) | दो `Point` ऑब्जेक्ट्स की तुलना करता है। परिणाम यह निर्दिष्ट करता है कि दो `Point` ऑब्जेक्ट्स की [`X`](./x/) या [`Y`](./y/) प्रॉपर्टीज़ के मान असमान हैं या नहीं। |
| [operator -](../../aspose.psd/point/op_subtraction/) | दिए गए [`Size`](../size/) के नकारात्मक द्वारा एक `Point` को ट्रांसलेट करता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


