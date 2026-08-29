---
title: "क्लास EllipseShape"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Shapes.EllipseShape क्लास। एक अंडाकार आकार का प्रतिनिधित्व करता है।"
type: docs
weight: 5990
url: /hi/net/aspose.psd.shapes/ellipseshape/
---
{{< psd/tize >}}
## EllipseShape class

एक एलिप्स आकार का प्रतिनिधित्व करता है।

```csharp
public class EllipseShape : RectangleShape
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | `EllipseShape` क्लास का नया उदाहरण इनिशियलाइज़ करता है। |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | `EllipseShape` क्लास का नया उदाहरण इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | आकार के केंद्र को प्राप्त करता है। |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि आकार में सेगमेंट हैं या नहीं। |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | बाएँ निचले आयत बिंदु को प्राप्त करता है। |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | बाएँ ऊपर के आयत बिंदु को प्राप्त करता है। |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | आयत की ऊँचाई को प्राप्त करता है। |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | आयत की चौड़ाई को प्राप्त करता है। |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | दाएँ निचले आयत बिंदु को प्राप्त करता है। |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | दाएँ ऊपर के आयत बिंदु को प्राप्त करता है। |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | आकार के खंडों को प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |

## उदाहरण

यह उदाहरण एक नई इमेज बनाता है और इमेज सतह पर फ़िगर्स और GraphicsPath का उपयोग करके विभिन्न आकारों को ड्रॉ करता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएँ।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाएं और प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करें।
    graphics.Clear(Color.Wheat);

    //GraphicsPath क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //फ़िगर ऑब्जेक्ट में आकार जोड़ें
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Figure क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //फ़िगर ऑब्जेक्ट में आकार जोड़ें
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //GraphicsPath में Figure ऑब्जेक्ट जोड़ें।
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //काली रंग की Pen ऑब्जेक्ट से पाथ ड्रॉ करें।
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // निर्यात विकल्प बनाएं और उन्हें प्रारंभ करें।
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // सभी परिवर्तन सहेजें।
    image.Save("c:\\temp\\output.bmp", options);
}
```

### देखें भी

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


