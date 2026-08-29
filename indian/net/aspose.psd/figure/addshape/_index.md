---
title: "Figure.AddShape"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Figure मेथड। चित्र में एक आकार जोड़ता है"
type: docs
weight: 60
url: /hi/net/aspose.psd/figure/addshape/
---
{{< psd/tize >}}
## Figure.AddShape method

फ़िगर में एक आकार जोड़ता है।

```csharp
public void AddShape(Shape shape)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| आकार | आकार | जोड़ने के लिए आकार। |

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

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


