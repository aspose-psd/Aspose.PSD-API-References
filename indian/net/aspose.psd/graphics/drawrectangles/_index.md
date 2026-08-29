---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics विधि। RectangleF संरचनाओं द्वारा निर्दिष्ट आयतों की श्रृंखला को बनाता है।"
type: docs
weight: 320
url: /hi/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

[`RectangleF`](../../rectanglef/) संरचनाओं द्वारा निर्दिष्ट आयतों की श्रृंखला को बनाता है।

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आयतों की रूपरेखाओं का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rects | RectangleF[] | ड्रॉ करने के लिए आयतों का प्रतिनिधित्व करने वाली [`RectangleF`](../../rectanglef/) संरचनाओं की सरणी। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *rects* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

[`Rectangle`](../../rectangle/) संरचनाओं द्वारा निर्दिष्ट आयतों की श्रृंखला को बनाता है।

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आयतों की रूपरेखाओं का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rects | Rectangle[] | ड्रॉ करने के लिए आयतों का प्रतिनिधित्व करने वाली [`Rectangle`](../../rectangle/) संरचनाओं की सरणी। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *rects* शून्य है। |

## उदाहरण

यह उदाहरण Pen ऑब्जेक्ट्स के निर्माण और उपयोग को दिखाता है। उदाहरण एक नई Image बनाता है और Image सतह पर Rectangles खींचता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएँ।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics का एक उदाहरण बनाएं और इसे Image ऑब्जेक्ट के साथ प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को White Color से साफ़ करें।
    graphics.Clear(Aspose.PSD.Color.White);

    //Pen का एक उदाहरण बनाएं, रंग Red और चौड़ाई 5 के साथ।
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush का एक उदाहरण बनाएं और उसकी गुण सेट करें।
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen का एक उदाहरण बनाएं।
    //इसे HatchBrush ऑब्जेक्ट और चौड़ाई के साथ प्रारंभ करें।
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen ऑब्जेक्ट निर्दिष्ट करके Rectangles खींचें।
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen ऑब्जेक्ट निर्दिष्ट करके Rectangles खींचें।
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // निर्यात विकल्प बनाएं और उन्हें प्रारंभ करें।
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // सभी परिवर्तन सहेजें।
    image.Save("c:\\temp\\output.jp2", options);
}
```

### देखें भी

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


