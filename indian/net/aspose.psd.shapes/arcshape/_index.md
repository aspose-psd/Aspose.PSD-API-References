---
title: Class ArcShape
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Shapes.ArcShape कक्ष. एक चप आकर क प्रतनधत्व करत है
type: docs
weight: 5460
url: /hi/net/aspose.psd.shapes/arcshape/
---
## ArcShape class

एक चाप आकार का प्रतिनिधित्व करता है।

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`ArcShape` वर्ग. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | का एक नया उदाहरण प्रारंभ करता है`ArcShape` वर्ग. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | का एक नया उदाहरण प्रारंभ करता है`ArcShape` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | वस्तु की सीमा प्राप्त करता है। |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | आकार का केंद्र प्राप्त करता है। |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | अंतिम आकार बिंदु प्राप्त करता है। |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | एक मान प्राप्त करता है जो बताता है कि आकार में खंड हैं या नहीं। |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि आदेशित आकार बंद है या नहीं। बंद आदेशित आकार को संसाधित करते समय प्रारंभ और समाप्ति बिंदुओं का कोई अर्थ नहीं होता है। |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | बाएँ तल का आयत बिंदु प्राप्त करता है। |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | बाएं शीर्ष आयत बिंदु प्राप्त करता है। |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | आयत ऊंचाई प्राप्त करता है। |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | आयत की चौड़ाई प्राप्त करता है। |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | दाएं तल का आयत बिंदु प्राप्त करता है। |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | दाहिने शीर्ष आयत बिंदु प्राप्त करता है। |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | आकार खंड प्राप्त करता है। |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | प्रारंभ कोण प्राप्त या सेट करता है। |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | प्रारंभिक आकार बिंदु प्राप्त करता है। |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | स्वीप कोण प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | वस्तु की सीमा प्राप्त करता है। |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | वस्तु की सीमा प्राप्त करता है। |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | इस आकृति के लिए बिंदुओं के क्रम को उलट देता है। |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार में लागू करता है। |

### उदाहरण

यह उदाहरण एक नई छवि बनाता है और छवि की सतह पर आंकड़े और ग्राफिक्सपाथ का उपयोग करके विभिन्न प्रकार की आकृतियाँ बनाता है

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // फिगर ऑब्जेक्ट में शेप जोड़ें
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // चित्र वर्ग का एक उदाहरण बनाएँ
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // फिगर ऑब्जेक्ट में शेप जोड़ें
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    // ग्राफिक्सपाथ में फिगर ऑब्जेक्ट जोड़ें
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // काले रंग के पेन ऑब्जेक्ट के साथ पथ बनाएं
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // निर्यात विकल्प बनाएं और उन्हें प्रारंभ करें।
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // सभी परिवर्तनों को सहेजें।
    image.Save("c:\\temp\\output.bmp", options);
}
```

### यह सभी देखें

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* नाम स्थान [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* सभा [Aspose.PSD](../../)


