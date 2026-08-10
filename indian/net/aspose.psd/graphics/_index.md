---
title: "क्लास Graphics"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Graphics क्लास। वर्तमान असेंबली में उपयोग किए गए ग्राफ़िक्स इंजन के अनुसार ग्राफ़िक्स का प्रतिनिधित्व करता है।"
type: docs
weight: 4780
url: /hi/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

वर्तमान असेंबली में उपयोग किए गए ग्राफ़िक्स इंजन के अनुसार ग्राफ़िक्स का प्रतिनिधित्व करता है।

```csharp
public sealed class Graphics
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Graphics](graphics/)(Image) | `Graphics` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | क्लिप रीजन को प्राप्त करता है या सेट करता है। |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | कॉम्पोज़िटिंग क्वालिटी को प्राप्त करता है या सेट करता है। |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | इस Aspose.PSD.Graphics की क्षैतिज रिज़ॉल्यूशन प्राप्त करता है। |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | इस Aspose.PSD.Graphics की लंबवत रिज़ॉल्यूशन प्राप्त करता है। |
| [Image](../../aspose.psd/graphics/image/) { get; } | इमेज प्राप्त करता है। |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | इंटरपोलेशन मोड प्राप्त करता है या सेट करता है। |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ग्राफ़िक्स BeginUpdate कॉल स्थिति में है या नहीं। |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | इस Aspose.PSD.Graphics के लिए विश्व इकाइयों और पेज इकाइयों के बीच स्केलिंग को प्राप्त करता है या सेट करता है। |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | इस Aspose.PSD.Graphics में पेज कॉर्डिनेट्स के लिए उपयोग की जाने वाली माप इकाई को प्राप्त करता है या सेट करता है। |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | इमेज विकल्प प्राप्त करता है या सेट करता है, जो ड्रॉ करने के लिए पेंटेबल वेक्टर इमेज बनाने में उपयोग होते हैं। |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | प्राप्त करता है या सेट करता है स्मूदिंग मोड। |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | प्राप्त करता है या सेट करता है पाठ रेंडरिंग संकेत। |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | `Graphics` के लिए ज्यामितीय विश्व परिवर्तन की एक प्रति प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | निम्नलिखित ग्राफ़िक्स ऑपरेशनों की कैशिंग शुरू करता है। बाद में लागू किए गए ग्राफ़िक्स इफ़ेक्ट्स तुरंत लागू नहीं होंगे, बल्कि EndUpdate सभी इफ़ेक्ट्स को एक साथ लागू करेगा। |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | निर्दिष्ट रंग का उपयोग करके ग्राफ़िक्स सतह को साफ़ करता है। |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | एक आर्क ड्रॉ करता है जो एक अंडाकार के उस हिस्से को दर्शाता है जिसे एक [`Rectangle`](../rectangle/) संरचना द्वारा निर्दिष्ट किया गया है। |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | एक आर्क ड्रॉ करता है जो एक अंडाकार के उस हिस्से को दर्शाता है जिसे एक [`RectangleF`](../rectanglef/) संरचना द्वारा निर्दिष्ट किया गया है। |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | एक आर्क ड्रॉ करता है जो एक अंडाकार के उस हिस्से को दर्शाता है जिसे निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट किया गया है। |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | एक आर्क ड्रॉ करता है जो एक अंडाकार के उस हिस्से को दर्शाता है जिसे निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट किया गया है। |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | चार [`Point`](../point/) संरचनाओं द्वारा परिभाषित एक Bézier स्प्लाइन बनाता है। |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | चार [`PointF`](../pointf/) संरचनाओं द्वारा परिभाषित एक Bézier स्प्लाइन बनाता है। |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | बिंदुओं का प्रतिनिधित्व करने वाले चार क्रमबद्ध निर्देशांक युग्मों द्वारा परिभाषित एक Bézier स्प्लाइन बनाता है। |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | [`PointF`](../pointf/) संरचनाओं की एक array से Bézier स्प्लाइन की श्रृंखला बनाता है। |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | [`Point`](../point/) संरचनाओं की एक array से Bézier स्प्लाइन की श्रृंखला बनाता है। |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | [`PointF`](../pointf/) संरचनाओं की एक array द्वारा परिभाषित एक बंद कार्डिनल स्प्लाइन बनाता है। यह विधि 0.5 की डिफ़ॉल्ट टेंशन और Alternate fill mode का उपयोग करती है। |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | [`Point`](../point/) संरचनाओं की एक array द्वारा परिभाषित एक बंद कार्डिनल स्प्लाइन बनाता है। यह विधि 0.5 की डिफ़ॉल्ट टेंशन और Alternate fill mode का उपयोग करती है। |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | [`PointF`](../pointf/) संरचनाओं की एक array द्वारा परिभाषित एक बंद कार्डिनल स्प्लाइन बनाता है, जिसमें निर्दिष्ट टेंशन का उपयोग किया जाता है। यह विधि डिफ़ॉल्ट Alternate fill mode का उपयोग करती है। |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | [`Point`](../point/) संरचनाओं की एक array द्वारा परिभाषित एक बंद कार्डिनल स्प्लाइन बनाता है, जिसमें निर्दिष्ट टेंशन का उपयोग किया जाता है। यह विधि डिफ़ॉल्ट Alternate fill mode का उपयोग करती है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | निर्दिष्ट [`PointF`](../pointf/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। यह विधि 0.5 की डिफ़ॉल्ट टेंशन का उपयोग करती है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | निर्दिष्ट [`Point`](../point/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | निर्दिष्ट [`PointF`](../pointf/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है, जिसमें निर्दिष्ट टेंशन का उपयोग किया जाता है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | निर्दिष्ट [`Point`](../point/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है, जिसमें निर्दिष्ट टेंशन का उपयोग किया जाता है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | निर्दिष्ट [`PointF`](../pointf/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है। चित्रण array की शुरुआत से ऑफ़सेट होकर शुरू होता है। यह विधि 0.5 की डिफ़ॉल्ट टेंशन का उपयोग करती है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | निर्दिष्ट [`PointF`](../pointf/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है, जिसमें निर्दिष्ट टेंशन का उपयोग किया जाता है। चित्रण array की शुरुआत से ऑफ़सेट होकर शुरू होता है। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | निर्दिष्ट [`Point`](../point/) संरचनाओं की array के माध्यम से एक कार्डिनल स्प्लाइन बनाता है, जिसमें निर्दिष्ट टेंशन का उपयोग किया जाता है। |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | एक बाउंडिंग [`Rectangle`](../rectangle/) संरचना द्वारा निर्दिष्ट एक अंडाकार बनाता है। |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | एक बाउंडिंग [`RectangleF`](../rectanglef/) द्वारा परिभाषित एक अंडाकार बनाता है। |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | एक बाउंडिंग आयत द्वारा परिभाषित अंडाकार, जो दो निर्देशांक युग्म, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट होता है, बनाता है। |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | एक बाउंडिंग आयत द्वारा परिभाषित अंडाकार, जो दो निर्देशांक युग्म, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट होता है, बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | निर्दिष्ट [`Image`](./image/) को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | निर्दिष्ट [`Image`](./image/) को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | निर्दिष्ट [`Image`](./image/) को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | निर्दिष्ट छवि को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | निर्दिष्ट [`Image`](./image/) को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | एक निर्दिष्ट छवि को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | एक निर्दिष्ट छवि को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | निर्दिष्ट छवि को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | एक निर्दिष्ट छवि को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर बनाता है। |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | निर्दिष्ट छवि को बिना स्केलिंग के बनाता है और यदि आवश्यक हो तो उसे क्लिप करता है, ताकि वह निर्दिष्ट आयत में फिट हो सके। |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | दो [`Point`](../point/) संरचनाओं को जोड़ती हुई एक रेखा बनाती है। |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | दो [`PointF`](../pointf/) संरचनाओं को जोड़ती हुई एक रेखा बनाती है। |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई एक रेखा बनाती है। |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई एक रेखा बनाती है। |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | एक सरणी में मौजूद [`PointF`](../pointf/) संरचनाओं को जोड़ने वाले रेखा खंडों की श्रृंखला बनाती है। |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | एक सरणी में मौजूद [`Point`](../point/) संरचनाओं को जोड़ने वाले रेखा खंडों की श्रृंखला बनाती है। |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | `[`GraphicsPath`](../graphicspath/)` बनाती है। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | `[`Rectangle`](../rectangle/)` संरचना और दो रेडियल रेखाओं द्वारा निर्दिष्ट एक दीर्घवृत्त द्वारा परिभाषित पाई आकार बनाती है। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | `[`RectangleF`](../rectanglef/)` संरचना और दो रेडियल रेखाओं द्वारा निर्दिष्ट एक दीर्घवृत्त द्वारा परिभाषित पाई आकार बनाती है। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | एक निर्देशांक युग्म, चौड़ाई, ऊँचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट एक दीर्घवृत्त द्वारा परिभाषित पाई आकार बनाती है। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | एक निर्देशांक युग्म, चौड़ाई, ऊँचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट एक दीर्घवृत्त द्वारा परिभाषित पाई आकार बनाती है। |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | `[`PointF`](../pointf/)` संरचनाओं की एक सरणी द्वारा परिभाषित बहुभुज बनाती है। |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | `[`Point`](../point/)` संरचनाओं की एक सरणी द्वारा परिभाषित बहुभुज बनाती है। |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | `[`Rectangle`](../rectangle/)` संरचना द्वारा निर्दिष्ट आयत बनाती है। |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | `[`RectangleF`](../rectanglef/)` संरचना द्वारा निर्दिष्ट आयत बनाती है। |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | एक निर्देशांक युग्म, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट आयत बनाती है। |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | एक निर्देशांक युग्म, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट आयत बनाती है। |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | `[`RectangleF`](../rectanglef/)` संरचनाओं द्वारा निर्दिष्ट आयतों की श्रृंखला बनाती है। |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | `[`Rectangle`](../rectangle/)` संरचनाओं द्वारा निर्दिष्ट आयतों की श्रृंखला बनाती है। |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [`Brush`](../brush/) और [`Font`](../font/) वस्तुओं के साथ बनाती है। |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [`Brush`](../brush/) और [`Font`](../font/) वस्तुओं के साथ बनाती है। |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [`Brush`](../brush/) और [`Font`](../font/) वस्तुओं के साथ बनाती है। |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [`Brush`](../brush/) और [`Font`](../font/) वस्तुओं के साथ, निर्दिष्ट [`StringFormat`](../stringformat/) के फ़ॉर्मेटिंग गुणों का उपयोग करके बनाती है। |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [`Brush`](../brush/) और [`Font`](../font/) वस्तुओं के साथ, निर्दिष्ट [`StringFormat`](../stringformat/) के फ़ॉर्मेटिंग गुणों का उपयोग करके बनाती है। |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट [`Brush`](../brush/) और [`Font`](../font/) वस्तुओं के साथ, निर्दिष्ट [`StringFormat`](../stringformat/) के फ़ॉर्मेटिंग गुणों का उपयोग करके बनाती है। |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | BeginUpdate को कॉल करने के बाद शुरू किए गए ग्राफ़िक्स ऑपरेशनों की कैशिंग समाप्त करता है। पूर्ववर्ती ग्राफ़िक्स ऑपरेशनों को इस मेथड को कॉल करने पर एक साथ लागू किया जाएगा। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | `[`PointF`](../pointf/)` संरचनाओं की एक सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन वक्र के अंदर को भरता है। यह मेथड डिफ़ॉल्ट तनाव 0.5 और वैकल्पिक भराव मोड का उपयोग करता है। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | `[`Point`](../point/)` संरचनाओं की एक सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन वक्र के अंदर को भरता है। यह मेथड डिफ़ॉल्ट तनाव 0.5 और वैकल्पिक भराव मोड का उपयोग करता है। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | `[`PointF`](../pointf/)` संरचनाओं की एक सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन वक्र के अंदर को निर्दिष्ट भराव मोड का उपयोग करके भरता है। यह मेथड डिफ़ॉल्ट तनाव 0.5 का उपयोग करता है। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | `[`Point`](../point/)` संरचनाओं की एक सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन वक्र के अंदर को निर्दिष्ट भराव मोड का उपयोग करके भरता है। यह मेथड डिफ़ॉल्ट तनाव 0.5 का उपयोग करता है। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | निर्दिष्ट फ़िल मोड और तनाव का उपयोग करके, एक एरे में परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है, जिसमें [`PointF`](../pointf/) संरचनाएँ हैं। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | निर्दिष्ट फ़िल मोड और तनाव का उपयोग करके, एक एरे में परिभाषित बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है, जिसमें [`Point`](../point/) संरचनाएँ हैं। |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | एक बाउंडिंग आयत द्वारा परिभाषित एलिप्स के अंदरूनी भाग को भरता है, जो एक [`Rectangle`](../rectangle/) संरचना द्वारा निर्दिष्ट है। |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | एक बाउंडिंग आयत द्वारा परिभाषित एलिप्स के अंदरूनी भाग को भरता है, जो एक [`RectangleF`](../rectanglef/) संरचना द्वारा निर्दिष्ट है। |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | एक जोड़े निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट बाउंडिंग आयत से परिभाषित एलिप्स के अंदरूनी भाग को भरता है। |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | एक जोड़े निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट बाउंडिंग आयत से परिभाषित एलिप्स के अंदरूनी भाग को भरता है। |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | एक [`GraphicsPath`](../graphicspath/) का अंदरूनी भाग भरता है। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | एक एलिप्स द्वारा परिभाषित पाई सेक्शन के अंदरूनी भाग को भरता है, जो एक [`RectangleF`](../rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट है। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | एक एलिप्स द्वारा परिभाषित पाई सेक्शन के अंदरूनी भाग को भरता है, जो एक [`RectangleF`](../rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट है। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | एक जोड़े निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट एलिप्स से परिभाषित पाई सेक्शन के अंदरूनी भाग को भरता है। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | एक जोड़े निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट एलिप्स से परिभाषित पाई सेक्शन के अंदरूनी भाग को भरता है। |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | एक एरे में बिंदुओं द्वारा परिभाषित बहुभुज के अंदरूनी भाग को भरता है, जो [`PointF`](../pointf/) संरचनाओं और Alternate द्वारा निर्दिष्ट है। |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | एक एरे में बिंदुओं द्वारा परिभाषित बहुभुज के अंदरूनी भाग को भरता है, जो [`Point`](../point/) संरचनाओं और Alternate द्वारा निर्दिष्ट है। |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | निर्दिष्ट फ़िल मोड का उपयोग करके, एक एरे में बिंदुओं द्वारा परिभाषित बहुभुज के अंदरूनी भाग को भरता है, जो [`PointF`](../pointf/) संरचनाओं द्वारा निर्दिष्ट है। |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | निर्दिष्ट फ़िल मोड का उपयोग करके, एक एरे में बिंदुओं द्वारा परिभाषित बहुभुज के अंदरूनी भाग को भरता है, जो [`Point`](../point/) संरचनाओं द्वारा निर्दिष्ट है। |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | एक [`Rectangle`](../rectangle/) संरचना द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है। |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | एक [`RectangleF`](../rectanglef/) संरचना द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है। |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | एक जोड़े निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है। |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | एक जोड़े निर्देशांक, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट आयत के अंदरूनी भाग को भरता है। |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | एक श्रृंखला में आयतों के अंदरूनी भाग को भरता है, जो [`RectangleF`](../rectanglef/) संरचनाओं द्वारा निर्दिष्ट हैं। |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | एक श्रृंखला में आयतों के अंदरूनी भाग को भरता है, जो [`Rectangle`](../rectangle/) संरचनाओं द्वारा निर्दिष्ट हैं। |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | एक [`Region`](../region/) का अंदरूनी भाग भरता है। |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | इस `Graphics` के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [`Matrix`](../matrix/) को निर्दिष्ट [`Matrix`](../matrix/) द्वारा, निर्दिष्ट [`Matrix`](../matrix/) को पहले जोड़कर, गुणा करता है। |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | इस `Graphics` के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले [`Matrix`](../matrix/) को निर्दिष्ट क्रम में निर्दिष्ट [`Matrix`](../matrix/) द्वारा गुणा करता है। |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | [`Transform`](./transform/) प्रॉपर्टी को पहचान पर रीसेट करता है। |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घूर्णन को रूपांतरण के पहले जोड़ता है। |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट मात्रा से घुमाता है। |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ता है। |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट मात्राओं से स्केल करता है। |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट आयामों से अनुवादित करता है। यह मेथड ट्रांसलेशन को रूपांतरण के पहले जोड़ता है। |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट क्रम में निर्दिष्ट आयामों से अनुवादित करता है। |

## उदाहरण

यह उदाहरण इमेज सतह पर मूल आकार बनाने के लिए Graphics क्लास का उपयोग करता है। संचालन को प्रदर्शित करने के लिए, उदाहरण PSD प्रारूप में एक नई इमेज बनाता है और Graphics क्लास द्वारा प्रदत्त Draw विधियों का उपयोग करके इमेज सतह पर मूल आकार खींचता है, फिर इसे PSD फ़ाइल प्रारूप में निर्यात करता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएं।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाएं और प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करें।
    graphics.Clear(Color.Wheat);

    //काली रंग वाले Pen ऑब्जेक्ट को निर्दिष्ट करके एक आर्क ड्रॉ करें, 
    //आर्क को घेरने वाला एक आयत, प्रारंभिक कोण और स्वीप कोण
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //नीले रंग वाले Pen ऑब्जेक्ट और निर्देशांक बिंदुओं को निर्दिष्ट करके एक बीज़ियर ड्रॉ करें।
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //हरे रंग वाले Pen ऑब्जेक्ट और बिंदुओं की एक श्रृंखला को निर्दिष्ट करके एक कर्व ड्रॉ करें
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen ऑब्जेक्ट और एक घेरने वाले आयत का उपयोग करके एक अंडाकार ड्रॉ करें
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //एक रेखा ड्रॉ करें 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //एक पाई सेगमेंट ड्रॉ करें
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //लाल रंग वाले Pen ऑब्जेक्ट और बिंदुओं की एक श्रृंखला को निर्दिष्ट करके एक बहुभुज ड्रॉ करें
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //एक आयत ड्रॉ करें
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //एक SolidBrush ऑब्जेक्ट बनाएं और उसकी विभिन्न गुण सेट करें
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush ऑब्जेक्ट और फ़ॉन्ट का उपयोग करके, विशिष्ट बिंदु पर एक स्ट्रिंग ड्रॉ करें
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions का एक उदाहरण बनाएं और उसकी विभिन्न गुण सेट करें
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


