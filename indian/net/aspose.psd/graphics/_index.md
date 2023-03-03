---
title: Class Graphics
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Graphics कक्ष. वर्तमन असेंबल में प्रयुक्त ग्रफक्स इंजन के अनुसर ग्रफक्स क प्रतनधत्व करत है
type: docs
weight: 4310
url: /hi/net/aspose.psd/graphics/
---
## Graphics class

वर्तमान असेंबली में प्रयुक्त ग्राफिक्स इंजन के अनुसार ग्राफिक्स का प्रतिनिधित्व करता है।

```csharp
public sealed class Graphics
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Graphics](graphics/)(Image) | का एक नया उदाहरण प्रारंभ करता है`Graphics` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | क्लिप क्षेत्र प्राप्त या सेट करता है। |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | कंपोज़िटिंग गुणवत्ता प्राप्त या सेट करता है। |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | इस Aspose.PSD.Graphics. का क्षैतिज रिज़ॉल्यूशन प्राप्त करता है |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | इस Aspose.PSD.Graphics. का लंबवत रिज़ॉल्यूशन प्राप्त करता है |
| [Image](../../aspose.psd/graphics/image/) { get; } | छवि प्राप्त करता है। |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | इंटरपोलेशन मोड प्राप्त या सेट करता है। |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि ग्राफ़िक्स BeginUpdate कॉल स्थिति में है या नहीं. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | इस Aspose.PSD.Graphics. के लिए विश्व इकाइयों और पृष्ठ इकाइयों के बीच स्केलिंग प्राप्त या सेट करता है |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | इस Aspose.PSD.Graphics. में पृष्ठ निर्देशांक के लिए उपयोग की जाने वाली माप की इकाई को प्राप्त या सेट करता है |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | स्मूथिंग मोड प्राप्त या सेट करता है। |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | टेक्स्ट रेंडरिंग संकेत प्राप्त या सेट करता है। |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | इसके लिए ज्यामितीय विश्व परिवर्तन की एक प्रति प्राप्त या सेट करता है`Graphics` . |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | निम्न ग्राफ़िक्स कार्रवाइयों की कैशिंग प्रारंभ करता है. बाद में लागू किए गए ग्राफ़िक्स प्रभाव तुरंत लागू नहीं होंगे, इसके बजाय एंडअपडेट एक बार में सभी प्रभावों को लागू कर देगा. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | निर्दिष्ट रंग का उपयोग करके ग्राफ़िक सतह को साफ़ करता है. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | द्वारा निर्दिष्ट अंडाकार के एक हिस्से का प्रतिनिधित्व करने वाला एक चाप खींचता है[`Rectangle`](../rectangle/)संरचना. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | द्वारा निर्दिष्ट अंडाकार के एक हिस्से का प्रतिनिधित्व करने वाला एक चाप खींचता है[`RectangleF`](../rectanglef/)संरचना. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | निर्देशांक, चौड़ाई और ऊंचाई की एक जोड़ी द्वारा निर्दिष्ट दीर्घवृत्त के एक हिस्से का प्रतिनिधित्व करने वाला एक चाप बनाता है। |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | निर्देशांक, चौड़ाई और ऊंचाई की एक जोड़ी द्वारा निर्दिष्ट दीर्घवृत्त के एक हिस्से का प्रतिनिधित्व करने वाला एक चाप बनाता है। |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | चार से परिभाषित बेज़ियर स्पलाइन बनाता है[`Point`](../point/) संरचनाएं. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | चार से परिभाषित बेज़ियर स्पलाइन बनाता है[`PointF`](../pointf/) संरचनाएं. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | बिंदुओं को दर्शाने वाले निर्देशांकों के चार क्रमित युग्मों द्वारा परिभाषित बेज़ियर स्पलाइन बनाता है। |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | की एक सरणी से बेज़ियर स्प्लाइन की एक श्रृंखला बनाता है[`PointF`](../pointf/) संरचनाएं. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | की एक सरणी से बेज़ियर स्प्लाइन की एक श्रृंखला बनाता है[`Point`](../point/) संरचनाएं. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन बनाता है[`PointF`](../pointf/) संरचनाएं। यह विधि 0.5 और के डिफ़ॉल्ट तनाव का उपयोग करती हैAlternate भरण मोड. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन बनाता है[`Point`](../point/) संरचनाएं। यह विधि 0.5 और के डिफ़ॉल्ट तनाव का उपयोग करती हैAlternate भरण मोड. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन बनाता है[`PointF`](../pointf/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। यह विधि डिफ़ॉल्ट का उपयोग करती हैAlternate भरण मोड. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन बनाता है[`Point`](../point/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। यह विधि डिफ़ॉल्ट का उपयोग करती हैAlternate भरण मोड. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../pointf/) संरचनाएं। यह विधि 0.5. के डिफ़ॉल्ट तनाव का उपयोग करती है |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`Point`](../point/) संरचनाएं. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../pointf/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`Point`](../point/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../pointf/) संरचनाएं। आरेखण सरणी की शुरुआत से ऑफसेट शुरू होता है। यह विधि 0.5. के डिफ़ॉल्ट तनाव का उपयोग करती है |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`PointF`](../pointf/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। आरेखण सरणी की शुरुआत से ऑफ़सेट प्रारंभ होता है. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | की एक निर्दिष्ट सरणी के माध्यम से एक कार्डिनल स्पलाइन बनाता है[`Point`](../point/) एक निर्दिष्ट तनाव का उपयोग कर संरचनाएं। |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | बाउंडिंग द्वारा निर्दिष्ट दीर्घवृत्त बनाता है[`Rectangle`](../rectangle/)संरचना. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | बाउंडिंग द्वारा परिभाषित दीर्घवृत्त बनाता है[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | निर्देशांक, ऊंचाई और चौड़ाई की एक जोड़ी द्वारा निर्दिष्ट बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त बनाता है। |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | निर्देशांक, ऊंचाई और चौड़ाई की एक जोड़ी द्वारा निर्दिष्ट बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करते हुए. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करते हुए. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करते हुए. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | एक निर्देशांक जोड़ी द्वारा निर्दिष्ट स्थान पर, अपने मूल भौतिक आकार का उपयोग करते हुए, निर्दिष्ट छवि बनाता है। |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | निर्दिष्ट के निर्दिष्ट भाग को खींचता है*image* निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | निर्दिष्ट आरेखित करता है[`Image`](./image/) निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | एक निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करके एक निर्दिष्ट छवि बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | एक निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करके एक निर्दिष्ट छवि बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | एक निर्देशांक जोड़ी द्वारा निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करके निर्दिष्ट छवि बनाता है। |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | एक निर्दिष्ट स्थान पर अपने मूल भौतिक आकार का उपयोग करके एक निर्दिष्ट छवि बनाता है। |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | निर्दिष्ट छवि को बिना स्केल किए बनाता है और निर्दिष्ट आयत में फिट होने के लिए, यदि आवश्यक हो, तो इसे क्लिप करता है। |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | दो को जोड़ने वाली एक रेखा खींचता है[`Point`](../point/) संरचनाएं. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | दो को जोड़ने वाली एक रेखा खींचता है[`PointF`](../pointf/) संरचनाएं. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | निर्देशांक जोड़े द्वारा निर्दिष्ट दो बिंदुओं को जोड़ने वाली एक रेखा खींचता है। |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | निर्देशांक जोड़े द्वारा निर्दिष्ट दो बिंदुओं को जोड़ने वाली एक रेखा खींचता है। |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | एक सरणी को जोड़ने वाले रेखा खंडों की एक श्रृंखला बनाता है[`PointF`](../pointf/) संरचनाएं. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | एक सरणी को जोड़ने वाले रेखा खंडों की एक श्रृंखला बनाता है[`Point`](../point/) संरचनाएं. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | आरेखित करता है[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | एक द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित एक पाई आकार बनाता है[`Rectangle`](../rectangle/) संरचना और दो रेडियल रेखाएँ। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | एक द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित एक पाई आकार बनाता है[`RectangleF`](../rectanglef/) संरचना और दो रेडियल रेखाएँ। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | एक समन्वय जोड़ी, चौड़ाई, ऊंचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित एक पाई आकार बनाता है। |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | एक समन्वय जोड़ी, चौड़ाई, ऊंचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित एक पाई आकार बनाता है। |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | एक सरणी द्वारा परिभाषित बहुभुज बनाता है[`PointF`](../pointf/) संरचनाएं. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | एक सरणी द्वारा परिभाषित बहुभुज बनाता है[`Point`](../point/) संरचनाएं. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | द्वारा निर्दिष्ट एक आयत बनाता है[`Rectangle`](../rectangle/)संरचना. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | द्वारा निर्दिष्ट एक आयत बनाता है[`RectangleF`](../rectanglef/)संरचना. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | एक निर्देशांक जोड़ी, एक चौड़ाई और एक ऊंचाई द्वारा निर्दिष्ट एक आयत बनाता है। |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | एक निर्देशांक जोड़ी, एक चौड़ाई और एक ऊंचाई द्वारा निर्दिष्ट एक आयत बनाता है। |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | निर्दिष्ट आयतों की एक श्रृंखला बनाता है[`RectangleF`](../rectanglef/) संरचनाएं. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | निर्दिष्ट आयतों की एक श्रृंखला बनाता है[`Rectangle`](../rectangle/) संरचनाएं. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../brush/) और[`Font`](../font/) वस्तुओं. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट आयत में निर्दिष्ट के साथ आरेखित करता है[`Brush`](../brush/) और[`Font`](../font/) वस्तुओं. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../brush/) और[`Font`](../font/) वस्तुओं. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../brush/) और[`Font`](../font/) निर्दिष्ट स्वरूपण विशेषताओं का उपयोग करके ऑब्जेक्ट[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट आयत में निर्दिष्ट के साथ आरेखित करता है[`Brush`](../brush/) और[`Font`](../font/) निर्दिष्ट स्वरूपण विशेषताओं का उपयोग करके ऑब्जेक्ट[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट स्थान पर निर्दिष्ट के साथ आरेखित करता है[`Brush`](../brush/) और[`Font`](../font/) निर्दिष्ट स्वरूपण विशेषताओं का उपयोग करके ऑब्जेक्ट[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | बिगिनअपडेट को कॉल करने के बाद शुरू हुए ग्राफिक्स ऑपरेशन की कैशिंग को खत्म करता है। इस विधि को कॉल करते समय पिछले ग्राफिक्स ऑपरेशन तुरंत लागू किए जाएंगे। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन वक्र के इंटीरियर को भरता है[`PointF`](../pointf/) संरचनाएं। यह विधि 0.5 और के डिफ़ॉल्ट तनाव का उपयोग करती हैAlternate भरण मोड. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन वक्र के इंटीरियर को भरता है[`Point`](../point/) संरचनाएं। यह विधि 0.5 और के डिफ़ॉल्ट तनाव का उपयोग करती हैAlternate भरण मोड. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन वक्र के इंटीरियर को भरता है[`PointF`](../pointf/) निर्दिष्ट भरण मोड का उपयोग करके संरचनाएं। यह विधि 0.5. के डिफ़ॉल्ट तनाव का उपयोग करती है |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन वक्र के इंटीरियर को भरता है[`Point`](../point/) निर्दिष्ट भरण मोड का उपयोग करके संरचनाएं। यह विधि 0.5. के डिफ़ॉल्ट तनाव का उपयोग करती है |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन वक्र के इंटीरियर को भरता है[`PointF`](../pointf/) निर्दिष्ट भरण मोड और तनाव का उपयोग करने वाली संरचनाएं। |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | एक सरणी द्वारा परिभाषित एक बंद कार्डिनल स्पलाइन वक्र के इंटीरियर को भरता है[`Point`](../point/) निर्दिष्ट भरण मोड और तनाव का उपयोग करने वाली संरचनाएं। |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | ए द्वारा निर्दिष्ट बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है[`Rectangle`](../rectangle/)संरचना. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | ए द्वारा निर्दिष्ट बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है[`RectangleF`](../rectanglef/)संरचना. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | निर्देशांक, चौड़ाई और ऊंचाई की एक जोड़ी द्वारा निर्दिष्ट बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है। |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | निर्देशांक, चौड़ाई और ऊंचाई की एक जोड़ी द्वारा निर्दिष्ट बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है। |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | एक के इंटीरियर को भरता है[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | एक द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित पाई अनुभाग के इंटीरियर को भरता है[`RectangleF`](../rectanglef/) संरचना और दो रेडियल रेखाएँ। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | एक द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित पाई अनुभाग के इंटीरियर को भरता है[`RectangleF`](../rectanglef/) संरचना और दो रेडियल रेखाएँ। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | निर्देशांकों की एक जोड़ी, एक चौड़ाई, एक ऊंचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित पाई अनुभाग के आंतरिक भाग को भरता है। |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | निर्देशांकों की एक जोड़ी, एक चौड़ाई, एक ऊंचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित पाई अनुभाग के आंतरिक भाग को भरता है। |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | द्वारा निर्दिष्ट बिंदुओं की एक सरणी द्वारा परिभाषित बहुभुज के आंतरिक भाग को भरता है[`PointF`](../pointf/) संरचनाएं औरAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | द्वारा निर्दिष्ट बिंदुओं की एक सरणी द्वारा परिभाषित बहुभुज के आंतरिक भाग को भरता है[`Point`](../point/) संरचनाएं औरAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | द्वारा निर्दिष्ट बिंदुओं की एक सरणी द्वारा परिभाषित बहुभुज के आंतरिक भाग को भरता है[`PointF`](../pointf/) निर्दिष्ट भरण मोड का उपयोग कर संरचनाएं। |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | द्वारा निर्दिष्ट बिंदुओं की एक सरणी द्वारा परिभाषित बहुभुज के आंतरिक भाग को भरता है[`Point`](../point/) निर्दिष्ट भरण मोड का उपयोग कर संरचनाएं। |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | a द्वारा निर्दिष्ट आयत के आंतरिक भाग को भरता है[`Rectangle`](../rectangle/)संरचना. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | a द्वारा निर्दिष्ट आयत के आंतरिक भाग को भरता है[`RectangleF`](../rectanglef/)संरचना. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | निर्देशांक, चौड़ाई और ऊंचाई की एक जोड़ी द्वारा निर्दिष्ट आयत के इंटीरियर को भरता है। |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | निर्देशांक, चौड़ाई और ऊंचाई की एक जोड़ी द्वारा निर्दिष्ट आयत के इंटीरियर को भरता है। |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | द्वारा निर्दिष्ट आयतों की एक श्रृंखला के अंदरूनी हिस्सों को भरता है[`RectangleF`](../rectanglef/) संरचनाएं. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | द्वारा निर्दिष्ट आयतों की एक श्रृंखला के अंदरूनी हिस्सों को भरता है[`Rectangle`](../rectangle/) संरचनाएं. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | एक के इंटीरियर को भरता है[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | गुणा करता है[`Matrix`](../matrix/) जो इसके स्थानीय ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है`Graphics` निर्दिष्ट द्वारा[`Matrix`](../matrix/) निर्दिष्ट तैयार करके[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | गुणा करता है[`Matrix`](../matrix/) जो इसके स्थानीय ज्यामितीय परिवर्तन का प्रतिनिधित्व करता है`Graphics` निर्दिष्ट द्वारा[`Matrix`](../matrix/) निर्दिष्ट क्रम में. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | रीसेट करता है[`Transform`](./transform/) पहचान के लिए संपत्ति। |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | निर्दिष्ट राशि से स्थानीय ज्यामितीय परिवर्तन को घुमाता है। यह विधि रोटेशन को परिवर्तन से पहले जोड़ती है। |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट राशि द्वारा स्थानीय ज्यामितीय परिवर्तन को घुमाता है। |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | निर्दिष्ट राशियों द्वारा स्थानीय ज्यामितीय परिवर्तन को मापता है। यह विधि स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म करने के लिए तैयार करती है। |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय परिवर्तन को स्केल करता है। |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। यह विधि ट्रांस्फ़ॉर्म के लिए अनुवाद को आगे बढ़ाती है. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन का अनुवाद करता है। |

### उदाहरण

यह उदाहरण छवि सतह पर आदिम आकार बनाने के लिए ग्राफिक्स वर्ग का उपयोग करता है। ऑपरेशन को प्रदर्शित करने के लिए, उदाहरण PSD प्रारूप में एक नई छवि बनाता है और ग्राफिक्स वर्ग द्वारा प्रदर्शित ड्रा विधियों का उपयोग करके छवि सतह पर आदिम आकृतियों को खींचता है और फिर इसे PSD फ़ाइल प्रारूप में निर्यात करता है।

```csharp
[C#]

// छवि का एक उदाहरण बनाएं 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स क्लास का एक उदाहरण बनाएं और आरंभ करें
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // स्पष्ट ग्राफिक्स सतह
    graphics.Clear(Color.Wheat);

    // ब्लैक कलर वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक आर्क बनाएं, 
    // आर्क के चारों ओर एक आयत, स्टार्ट एंगल और स्वीप एंगल
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // ब्लू कलर और को-ऑर्डिनेट पॉइंट वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक बेज़ियर ड्रा करें।
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // हरे रंग और बिंदुओं की एक सरणी वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक वक्र बनाएं
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // पेन ऑब्जेक्ट और आसपास के आयत का उपयोग करके एक दीर्घवृत्त बनाएं
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //एक रेखा खींचो 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // पाई सेगमेंट ड्रा करें
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // पेन ऑब्जेक्ट को लाल रंग और बिंदुओं की एक सरणी निर्दिष्ट करके एक बहुभुज बनाएं
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // एक आयत बनाएं
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    // एक सॉलिडब्रश ऑब्जेक्ट बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // विशिष्ट बिंदु पर सॉलिडब्रश ऑब्जेक्ट और फ़ॉन्ट का उपयोग करके एक स्ट्रिंग बनाएं
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // सभी परिवर्तनों को सहेजें।
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


