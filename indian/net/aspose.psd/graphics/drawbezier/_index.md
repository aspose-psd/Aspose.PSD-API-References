---
title: Graphics.DrawBezier
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Graphics तरक. बंदुओं क दर्शने वले नर्देशंकं के चर क्रमत युग्मं द्वर परभषत बेज़यर स्पलइन बनत है
type: docs
weight: 170
url: /hi/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

बिंदुओं को दर्शाने वाले निर्देशांकों के चार क्रमित युग्मों द्वारा परिभाषित बेज़ियर स्पलाइन बनाता है।

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x1 | Single | वक्र के शुरुआती बिंदु का x-निर्देशांक। |
| y1 | Single | वक्र के शुरुआती बिंदु का y-निर्देशांक। |
| x2 | Single | वक्र के पहले नियंत्रण बिंदु का x-निर्देशांक। |
| y2 | Single | वक्र के पहले नियंत्रण बिंदु का y-निर्देशांक। |
| x3 | Single | वक्र के दूसरे नियंत्रण बिंदु का x-निर्देशांक। |
| y3 | Single | वक्र के दूसरे नियंत्रण बिंदु का y-निर्देशांक। |
| x4 | Single | वक्र के अंतिम बिंदु का x-निर्देशांक। |
| y4 | Single | वक्र के अंतिम बिंदु का y-निर्देशांक। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

चार से परिभाषित बेज़ियर स्पलाइन बनाता है[`PointF`](../../pointf/) संरचनाएं.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो वक्र के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| pt1 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के शुरुआती बिंदु का प्रतिनिधित्व करती है। |
| pt2 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के लिए पहले नियंत्रण बिंदु का प्रतिनिधित्व करती है। |
| pt3 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के लिए दूसरे नियंत्रण बिंदु का प्रतिनिधित्व करती है। |
| pt4 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के अंतिम बिंदु का प्रतिनिधित्व करती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

चार से परिभाषित बेज़ियर स्पलाइन बनाता है[`Point`](../../point/) संरचनाएं.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) संरचना जो वक्र के रंग, चौड़ाई और शैली को निर्धारित करती है। |
| pt1 | Point | [`Point`](../../point/) संरचना जो वक्र के शुरुआती बिंदु का प्रतिनिधित्व करती है। |
| pt2 | Point | [`Point`](../../point/) संरचना जो वक्र के लिए पहले नियंत्रण बिंदु का प्रतिनिधित्व करती है। |
| pt3 | Point | [`Point`](../../point/) संरचना जो वक्र के लिए दूसरे नियंत्रण बिंदु का प्रतिनिधित्व करती है। |
| pt4 | Point | [`Point`](../../point/) संरचना जो वक्र के अंतिम बिंदु का प्रतिनिधित्व करती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### यह सभी देखें

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* नाम स्थान [Aspose.PSD](../../graphics/)
* सभा [Aspose.PSD](../../../)


