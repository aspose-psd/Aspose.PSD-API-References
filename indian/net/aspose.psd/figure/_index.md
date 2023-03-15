---
title: Class Figure
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Figure कक्ष. आंकड़ आकृतयं के लए एक कंटेनर
type: docs
weight: 1200
url: /hi/net/aspose.psd/figure/
---
## Figure class

आंकड़ा। आकृतियों के लिए एक कंटेनर।

```csharp
public class Figure : ObjectWithBounds
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Figure](figure/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | ऑब्जेक्ट की सीमा प्राप्त या सेट करता है। |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | यह दर्शाता है कि यह आंकड़ा बंद है या नहीं, यह मान प्राप्त करता है या सेट करता है। एक बंद आकृति केवल उस स्थिति में अंतर लाएगी जहां पहली और अंतिम आकृति के आकार निरंतर आकार हैं। ऐसे मामले में पहली आकृति का पहला बिंदु अंतिम आकृति के अंतिम बिंदु से एक सीधी रेखा से जुड़ा होगा. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | पूरे आंकड़े खंड प्राप्त करता है। |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | आकृति का आकार प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | आकृति में एक आकृति जोड़ता है। |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | आकृति में आकृतियों की एक श्रृंखला जोड़ता है। |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | वस्तु की सीमा प्राप्त करता है। |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | वस्तु की सीमा प्राप्त करता है। |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | आकृति से एक आकृति निकालता है। |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | आकृति से आकृतियों की एक श्रृंखला को हटाता है। |
| [Reverse](../../aspose.psd/figure/reverse/)() | इस आकृति के आकार क्रम को उलट देता है और बिंदु क्रम को आकार देता है। |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | निर्दिष्ट परिवर्तन को आकार में लागू करता है। |

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


