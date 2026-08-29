---
title: "क्लास Figure"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Figure क्लास। फ़िगर। आकारों के लिए कंटेनर"
type: docs
weight: 1210
url: /hi/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

फ़िगर। आकारों के लिए एक कंटेनर।

```csharp
public class Figure : ObjectWithBounds
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Figure](figure/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | ऑब्जेक्ट की सीमाएँ प्राप्त करता है या सेट करता है। |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | यह निर्धारित करने के लिए मान प्राप्त करता है या सेट करता है कि यह फ़िगर बंद है या नहीं। एक बंद फ़िगर केवल तब अंतर लाता है जब पहले और अंतिम फ़िगर के आकार सतत आकार हों। ऐसे मामले में पहले आकार का पहला बिंदु अंतिम आकार के अंतिम बिंदु से एक सीधी रेखा द्वारा जुड़ा होगा। |
| [Segments](../../aspose.psd/figure/segments/) { get; } | पूरे फ़िगर सेगमेंट प्राप्त करता है। |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | फ़िगर के आकार प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | फ़िगर में एक आकार जोड़ता है। |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | आकृति में आकारों की एक श्रृंखला जोड़ता है। |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | आकृति से एक आकार हटाता है। |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | आकृति से आकारों की एक श्रृंखला हटाता है। |
| [Reverse](../../aspose.psd/figure/reverse/)() | इस आकृति के आकारों के क्रम और आकार बिंदुओं के क्रम को उलटता है। |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |

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


