---
title: GraphicsPath.AddFigures
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: GraphicsPath तरक. नए आंकड़े जड़त है
type: docs
weight: 60
url: /hi/net/aspose.psd/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

नए आंकड़े जोड़ता है।

```csharp
public void AddFigures(Figure[] figures)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figures | Figure[] | जोड़ने के आंकड़े। |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* नाम स्थान [Aspose.PSD](../../graphicspath/)
* सभा [Aspose.PSD](../../../)


