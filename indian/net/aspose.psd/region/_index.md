---
title: "क्लास Region"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Region क्लास। आयतों और पाथ्स से बनी ग्राफ़िक्स आकार के अंदरूनी भाग का वर्णन करता है। यह क्लास इनहेरिट नहीं की जा सकती।"
type: docs
weight: 5860
url: /hi/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

आयत और पाथ से बनी ग्राफ़िक्स आकृति के अंदरूनी हिस्से का वर्णन करता है। इस क्लास को विरासत में नहीं लिया जा सकता।

```csharp
public sealed class Region
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Region](region/#constructor)() | एक नया `Region` प्रारंभ करता है। |
| [Region](region/#constructor_1)(GraphicsPath) | निर्दिष्ट [`GraphicsPath`](../graphicspath/) के साथ एक नया `Region` प्रारंभ करता है। |
| [Region](region/#constructor_2)(Rectangle) | निर्दिष्ट [`Rectangle`](../rectangle/) संरचना से एक नया `Region` प्रारंभ करता है। |
| [Region](region/#constructor_3)(RectangleF) | निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना से एक नया `Region` आरंभ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | इस `Region` को अपडेट करता है ताकि यह निर्दिष्ट [`GraphicsPath`](../graphicspath/) का वह भाग शामिल करे जो इस `Region` के साथ प्रतिच्छेद नहीं करता। |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | इस `Region` को अपडेट करता है ताकि यह निर्दिष्ट [`Rectangle`](../rectangle/) संरचना का वह भाग शामिल करे जो इस `Region` के साथ प्रतिच्छेद नहीं करता। |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | इस `Region` को अपडेट करता है ताकि यह निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना का वह भाग शामिल करे जो इस `Region` के साथ प्रतिच्छेद नहीं करता। |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | इस `Region` को अपडेट करता है ताकि यह निर्दिष्ट `Region` का वह भाग शामिल करे जो इस `Region` के साथ प्रतिच्छेद नहीं करता। |
| [DeepClone](../../aspose.psd/region/deepclone/)() | इस `Region` की एक सटीक गहरी प्रतिलिपि बनाता है। |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | जाँचें कि ऑब्जेक्ट समान हैं या नहीं। |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | जाँचता है कि क्या निर्दिष्ट `Region` इस `Region` के समान है निर्दिष्ट ड्रॉइंग सतह पर। |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | इस `Region` को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट [`GraphicsPath`](../graphicspath/) के साथ प्रतिच्छेद नहीं करता। |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | इस `Region` को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट [`Rectangle`](../rectangle/) संरचना के साथ प्रतिच्छेद नहीं करता। |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | इस `Region` को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना के साथ प्रतिच्छेद नहीं करता। |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | इस `Region` को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट `Region` के साथ प्रतिच्छेद नहीं करता। |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | वर्तमान ऑब्जेक्ट का हैश कोड प्राप्त करें। |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | इस `Region` को अपडेट करता है ताकि यह स्वयं और निर्दिष्ट [`GraphicsPath`](../graphicspath/) के प्रतिच्छेद को दर्शाए। |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | इस `Region` को अपडेट करता है ताकि यह स्वयं और निर्दिष्ट [`Rectangle`](../rectangle/) संरचना के प्रतिच्छेद को दर्शाए। |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | इस `Region` को अपडेट करता है ताकि यह स्वयं और निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना के प्रतिच्छेद को दर्शाए। |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | इस `Region` को अपडेट करता है ताकि यह स्वयं और निर्दिष्ट `Region` के प्रतिच्छेद को दर्शाए। |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | जाँचता है कि क्या इस `Region` का आंतरिक भाग निर्दिष्ट ड्रॉइंग सतह पर खाली है। |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | जाँचता है कि क्या इस `Region` का आंतरिक भाग निर्दिष्ट ड्रॉइंग सतह पर अनंत है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | जाँचता है कि क्या निर्दिष्ट [`Point`](../point/) संरचना इस `Region` के भीतर सम्मिलित है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | जाँचता है कि क्या निर्दिष्ट [`PointF`](../pointf/) संरचना इस `Region` के भीतर सम्मिलित है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | जाँचता है कि क्या निर्दिष्ट [`Rectangle`](../rectangle/) संरचना का कोई भी भाग इस `Region` के भीतर सम्मिलित है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | जाँचता है कि क्या निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना का कोई भी भाग इस `Region` के भीतर सम्मिलित है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | जाँचता है कि क्या निर्दिष्ट बिंदु इस `Region` के भीतर सम्मिलित है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | जाँचता है कि क्या निर्दिष्ट [`Point`](../point/) संरचना इस `Region` के भीतर सम्मिलित है जब इसे निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके चित्रित किया जाता है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | जाँचता है कि क्या निर्दिष्ट [`PointF`](../pointf/) संरचना इस `Region` के भीतर सम्मिलित है जब इसे निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके चित्रित किया जाता है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | जाँचता है कि क्या निर्दिष्ट [`Rectangle`](../rectangle/) संरचना का कोई भी भाग इस `Region` के भीतर सम्मिलित है जब इसे निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके चित्रित किया जाता है। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | परीक्षण करता है कि निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना का कोई भी भाग इस `Region` के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके बनाया गया हो। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | परीक्षण करता है कि निर्दिष्ट बिंदु इस `Region` के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके बनाया गया हो। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | परीक्षण करता है कि निर्दिष्ट बिंदु इस `Region` ऑब्जेक्ट के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट [`Graphics`](../graphics/) ऑब्जेक्ट का उपयोग करके बनाया गया हो। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | परीक्षण करता है कि निर्दिष्ट आयत का कोई भी भाग इस `Region` के भीतर सम्मिलित है या नहीं। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | परीक्षण करता है कि निर्दिष्ट आयत का कोई भी भाग इस `Region` के भीतर सम्मिलित है या नहीं। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | परीक्षण करता है कि निर्दिष्ट आयत का कोई भी भाग इस `Region` के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके बनाया गया हो। |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | परीक्षण करता है कि निर्दिष्ट आयत का कोई भी भाग इस `Region` के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट [`Graphics`](../graphics/) का उपयोग करके बनाया गया हो। |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | इस `Region` को खाली आंतरिक भाग में प्रारंभ करता है। |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | इस `Region` ऑब्जेक्ट को अनंत आंतरिक भाग में प्रारंभ करता है। |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | निर्दिष्ट [`Matrix`](../matrix/) द्वारा इस `Region` को रूपांतरित करता है। |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | निर्दिष्ट मात्रा द्वारा इस `Region` के निर्देशांक को ऑफसेट करता है। |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | निर्दिष्ट मात्रा द्वारा इस `Region` के निर्देशांक को ऑफसेट करता है। |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | इस `Region` को स्वयं और निर्दिष्ट [`GraphicsPath`](../graphicspath/) के संघ में अद्यतन करता है। |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | इस `Region` को स्वयं और निर्दिष्ट [`Rectangle`](../rectangle/) संरचना के संघ में अद्यतन करता है। |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | इस `Region` को स्वयं और निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना के संघ में अद्यतन करता है। |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | इस `Region` को स्वयं और निर्दिष्ट `Region` के संघ में अद्यतन करता है। |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | इस `Region` को स्वयं और निर्दिष्ट [`GraphicsPath`](../graphicspath/) के प्रतिच्छेदन को घटाकर संघ में अद्यतन करता है। |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | इस `Region` को स्वयं और निर्दिष्ट [`Rectangle`](../rectangle/) संरचना के प्रतिच्छेदन को घटाकर संघ में अद्यतन करता है। |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | इस `Region` को स्वयं और निर्दिष्ट [`RectangleF`](../rectanglef/) संरचना के प्रतिच्छेदन को घटाकर संघ में अद्यतन करता है। |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | इस `Region` को स्वयं और निर्दिष्ट `Region` के प्रतिच्छेदन को घटाकर संघ में अद्यतन करता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


