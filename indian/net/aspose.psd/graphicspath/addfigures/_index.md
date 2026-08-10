---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GraphicsPath मेथड। नई आकृतियों को जोड़ता है"
type: docs
weight: 60
url: /hi/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

नए आकृतियों को जोड़ता है।

```csharp
public void AddFigures(Figure[] figures)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| आकृतियाँ | Figure[] | जोड़ने के लिए आकृतियाँ। |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


