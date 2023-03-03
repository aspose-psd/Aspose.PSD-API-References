---
title: Class GraphicsPath
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.GraphicsPath कक्ष. जुड़ हुई रेखओं और वक्रं क एक श्रृंखल क प्रतनधत्व करत है इस वर्ग क इनहेरट नहं कय ज सकत.
type: docs
weight: 4320
url: /hi/net/aspose.psd/graphicspath/
---
## GraphicsPath class

जुड़ी हुई रेखाओं और वक्रों की एक श्रृंखला का प्रतिनिधित्व करता है। इस वर्ग को इनहेरिट नहीं किया जा सकता.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`GraphicsPath` वर्ग. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | का एक नया उदाहरण प्रारंभ करता है`GraphicsPath` वर्ग. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | का एक नया उदाहरण प्रारंभ करता है`GraphicsPath` वर्ग. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | का एक नया उदाहरण प्रारंभ करता है`GraphicsPath` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | ऑब्जेक्ट की सीमा प्राप्त या सेट करता है। |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | पथ आंकड़े प्राप्त करता है। |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | हो जाता है या सेट करता है[`FillMode`](../fillmode/) गणना जो यह निर्धारित करती है कि इसमें आकृतियों की आंतरिक सज्जा कैसी है`GraphicsPath` भरे हुए हैं. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | एक नया आंकड़ा जोड़ता है। |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | नए आंकड़े जोड़ता है। |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | निर्दिष्ट को जोड़ता है`GraphicsPath` इस पथ के लिए. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | निर्दिष्ट को जोड़ता है`GraphicsPath` इस पथ के लिए. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | इस ग्राफिक्स पथ का एक गहरा क्लोन करता है। |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | इस पथ में प्रत्येक वक्र को कनेक्टेड लाइन सेगमेंट के अनुक्रम में परिवर्तित करता है। |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | निर्दिष्ट परिवर्तन लागू करता है और फिर इसमें प्रत्येक वक्र को परिवर्तित करता है`GraphicsPath` कनेक्टेड लाइन सेगमेंट के अनुक्रम में। |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | इसमें प्रत्येक वक्र को परिवर्तित करता है`GraphicsPath` कनेक्टेड लाइन सेगमेंट के अनुक्रम में। |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | वस्तु की सीमा प्राप्त करता है। |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | वस्तु की सीमा प्राप्त करता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) और निर्दिष्ट का उपयोग करना[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) और निर्दिष्ट का उपयोग करना[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) और निर्दिष्ट का उपयोग करना[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इस की रूपरेखा के भीतर (नीचे) निहित है या नहीं`GraphicsPath` जब निर्दिष्ट के साथ खींचा गया[`Pen`](../pen/) और निर्दिष्ट का उपयोग करना[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` निर्दिष्ट के दृश्य क्लिप क्षेत्र में[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | इंगित करता है कि निर्दिष्ट बिंदु इसमें शामिल है या नहीं`GraphicsPath` , निर्दिष्ट का उपयोग कर[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | एक आंकड़ा निकालता है। |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | आंकड़े निकालता है। |
| [Reset](../../aspose.psd/graphicspath/reset/)() | ग्राफिक्स पथ को खाली करता है और सेट करता है[`FillMode`](../fillmode/) कोAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | इसके प्रत्येक आकार में आकृतियों, आकृतियों और बिंदुओं के क्रम को उलट देता है`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार में लागू करता है। |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | इसके लिए एक आयत और एक समांतर चतुर्भुज द्वारा परिभाषित एक ताना परिवर्तन लागू करता है`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | इसके लिए एक आयत और एक समांतर चतुर्भुज द्वारा परिभाषित एक ताना परिवर्तन लागू करता है`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | इसके लिए एक आयत और एक समांतर चतुर्भुज द्वारा परिभाषित एक ताना परिवर्तन लागू करता है`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | इसके लिए एक आयत और एक समांतर चतुर्भुज द्वारा परिभाषित एक ताना परिवर्तन लागू करता है`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | पथ में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | में एक अतिरिक्त रूपरेखा जोड़ता है`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | इसे बदलता है`GraphicsPath` वक्र के साथ जो उस क्षेत्र को घेरता है जो निर्दिष्ट पेन द्वारा इस पथ को खींचे जाने पर भर जाता है। |

### उदाहरण

यह उदाहरण एक छवि सतह पर आंकड़े बनाने और हेरफेर करने के लिए ग्राफ़िक्सपाथ और ग्राफ़िक्स वर्ग का उपयोग करते हैं। उदाहरण एक नई छवि बनाता है और ग्राफिक्सपाथ वर्ग की मदद से पथ बनाता है। अंत में ग्राफिक्स वर्ग द्वारा प्रदर्शित ड्रॉपाथ विधि को सतह पर पथ प्रस्तुत करने के लिए बुलाया जाता है। अंत में छवि को टिफ़ फ़ाइल स्वरूप में निर्यात किया जाता है।

```csharp
[C#]

// छवि का एक उदाहरण बनाएं 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स क्लास का एक उदाहरण बनाएं और आरंभ करें
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // स्पष्ट ग्राफिक्स सतह
    graphics.Clear(Color.Wheat);

    // ग्राफिक्सपाथ क्लास का एक उदाहरण बनाएं
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // चित्र वर्ग का एक उदाहरण बनाएँ
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // चित्र वस्तु में आकृतियाँ जोड़ें
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // ग्राफिक्सपाथ में फिगर ऑब्जेक्ट जोड़ें
    graphicspath.AddFigure(figure);

    // काले रंग के पेन ऑब्जेक्ट के साथ पथ बनाएं
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // TiffOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // सभी परिवर्तनों को सहेजें।
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### यह सभी देखें

* class [ObjectWithBounds](../objectwithbounds/)
* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)


