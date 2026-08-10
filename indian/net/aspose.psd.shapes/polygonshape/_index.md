---
title: "क्लास PolygonShape"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Shapes.PolygonShape क्लास। एक बहुभुज आकार का प्रतिनिधित्व करता है"
type: docs
weight: 6010
url: /hi/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

एक पॉलीगॉन आकार का प्रतिनिधित्व करता है।

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | `PolygonShape` क्लास का एक नया उदाहरण आरंभ करता है। |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | `PolygonShape` क्लास का एक नया उदाहरण आरंभ करता है। |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | `PolygonShape` क्लास का एक नया उदाहरण आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | आकार के केंद्र को प्राप्त करता है। |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | समाप्ति आकार बिंदु को प्राप्त करता है। |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि आकार में सेगमेंट हैं या नहीं। |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं। |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | वक्र बिंदुओं को प्राप्त करता या सेट करता है। |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | आकार के खंडों को प्राप्त करता है। |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | प्रारंभिक आकार बिंदु को प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | इस आकार के बिंदुओं के क्रम को उलटता है। |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


