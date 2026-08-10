---
title: "क्लास GraphicsPath"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.GraphicsPath क्लास। जुड़े हुए लाइनों और कर्व्स की श्रृंखला का प्रतिनिधित्व करता है। इस क्लास को विरासत में नहीं लिया जा सकता।"
type: docs
weight: 4790
url: /hi/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

जुड़े हुए रेखाओं और वक्रों की एक श्रृंखला का प्रतिनिधित्व करता है। इस क्लास को विरासत में नहीं लिया जा सकता।

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | `GraphicsPath` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | `GraphicsPath` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | `GraphicsPath` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | `GraphicsPath` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | ऑब्जेक्ट की सीमाएँ प्राप्त करता है या सेट करता है। |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | पाथ फ़िगर्स को प्राप्त करता है। |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | इस `GraphicsPath` में आकृतियों के अंदरूनी भाग को कैसे भरा जाता है, यह निर्धारित करने वाला [`FillMode`](../fillmode/) enumeration प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | एक नया आकृति जोड़ता है। |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | नए आकृतियों को जोड़ता है। |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | निर्दिष्ट `GraphicsPath` को इस पथ में जोड़ता है। |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | निर्दिष्ट `GraphicsPath` को इस पथ में जोड़ता है। |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | इस ग्राफ़िक्स पथ की गहरी क्लोन बनाता है। |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | इस पथ में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है। |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | निर्दिष्ट ट्रांसफ़ॉर्म लागू करता है और फिर इस `GraphicsPath` में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है। |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | इस `GraphicsPath` में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में बदलता है। |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है और निर्दिष्ट [`Graphics`](../graphics/) का उपयोग किया जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है और निर्दिष्ट [`Graphics`](../graphics/) का उपयोग किया जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है और निर्दिष्ट [`Graphics`](../graphics/) का उपयोग किया जाता है। |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` की रूपरेखा के भीतर (के नीचे) है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [`Pen`](../pen/) से खींचा जाता है और निर्दिष्ट [`Graphics`](../graphics/) का उपयोग किया जाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है, जब यह निर्दिष्ट [`Graphics`](../graphics/) के दृश्यमान क्लिप क्षेत्र में हो। |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | निर्दिष्ट बिंदु इस `GraphicsPath` के भीतर है या नहीं, यह दर्शाता है, जब निर्दिष्ट [`Graphics`](../graphics/) का उपयोग किया जाता है। |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | एक आकृति हटाता है। |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | आकृतियों को हटाता है। |
| [Reset](../../aspose.psd/graphicspath/reset/)() | ग्राफ़िक्स पथ को खाली करता है और [`FillMode`](../fillmode/) को Alternate पर सेट करता है। |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | इस `GraphicsPath` की प्रत्येक आकृति में आकृतियों, आकारों और बिंदुओं का क्रम उलट देता है। |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित warp ट्रांसफ़ॉर्म को इस `GraphicsPath` पर लागू करता है। |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित warp ट्रांसफ़ॉर्म को इस `GraphicsPath` पर लागू करता है। |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित warp ट्रांसफ़ॉर्म को इस `GraphicsPath` पर लागू करता है। |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित warp ट्रांसफ़ॉर्म को इस `GraphicsPath` पर लागू करता है। |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | पथ में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | `GraphicsPath` में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | इस `GraphicsPath` को उन वक्रों से बदलता है जो उस क्षेत्र को घेरते हैं जो निर्दिष्ट पेन द्वारा इस पथ को खींचे जाने पर भरा जाता है। |

## उदाहरण

यह उदाहरण GraphicsPath और Graphics क्लास का उपयोग करके Image सतह पर फ़िगर्स बनाता और संशोधित करता है। उदाहरण एक नया Image बनाता है और GraphicsPath क्लास की मदद से पाथ्स ड्रॉ करता है। अंत में Graphics क्लास द्वारा प्रदान किया गया DrawPath मेथड कॉल किया जाता है ताकि पाथ्स को सतह पर रेंडर किया जा सके। अंत में इमेज को Tiff फ़ाइल फ़ॉर्मेट में निर्यात किया जाता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएं।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाएं और प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करें।
    graphics.Clear(Color.Wheat);

    //GraphicsPath क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure ऑब्जेक्ट में शेप्स जोड़ें।
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath में Figure ऑब्जेक्ट जोड़ें।
    graphicspath.AddFigure(figure);

    //काली रंग की Pen ऑब्जेक्ट से पाथ ड्रॉ करें।
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions का एक इंस्टेंस बनाएं और उसकी विभिन्न प्रॉपर्टीज़ सेट करें।
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### देखें भी

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


