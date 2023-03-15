---
title: Figure.AddShape
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Figure तरक. आकृत में एक आकृत जड़त है
type: docs
weight: 60
url: /hi/net/aspose.psd/figure/addshape/
---
## Figure.AddShape method

आकृति में एक आकृति जोड़ता है।

```csharp
public void AddShape(Shape shape)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| shape | Shape | जोड़ने के लिए आकार। |

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

* class [Shape](../../shape/)
* class [Figure](../)
* नाम स्थान [Aspose.PSD](../../figure/)
* सभा [Aspose.PSD](../../../)


