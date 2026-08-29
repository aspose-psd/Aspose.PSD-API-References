---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। चार क्रमबद्ध निर्देशांक युग्मों द्वारा परिभाषित Bézier स्प्लाइन को ड्रॉ करता है जो बिंदुओं का प्रतिनिधित्व करते हैं।"
type: docs
weight: 180
url: /hi/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

बिंदुओं का प्रतिनिधित्व करने वाले चार क्रमबद्ध निर्देशांक युग्मों द्वारा परिभाषित एक Bézier स्प्लाइन बनाता है।

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो कर्व का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x1 | Single | कर्व के प्रारंभ बिंदु का x-निर्देशांक। |
| y1 | Single | कर्व के प्रारंभ बिंदु का y-निर्देशांक। |
| x2 | Single | कर्व के पहले नियंत्रण बिंदु का x-निर्देशांक। |
| y2 | Single | कर्व के पहले नियंत्रण बिंदु का y-निर्देशांक। |
| x3 | Single | कर्व के दूसरे नियंत्रण बिंदु का x-निर्देशांक। |
| y3 | Single | कर्व के दूसरे नियंत्रण बिंदु का y-निर्देशांक। |
| x4 | Single | कर्व के समाप्ति बिंदु का x-निर्देशांक। |
| y4 | Single | कर्व के समाप्ति बिंदु का y-निर्देशांक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

चार [`PointF`](../../pointf/) संरचनाओं द्वारा परिभाषित Bézier स्प्लाइन को ड्रॉ करता है।

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो कर्व का रंग, चौड़ाई और शैली निर्धारित करता है। |
| pt1 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के प्रारंभिक बिंदु को दर्शाती है। |
| pt2 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के पहले नियंत्रण बिंदु को दर्शाती है। |
| pt3 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के दूसरे नियंत्रण बिंदु को दर्शाती है। |
| pt4 | PointF | [`PointF`](../../pointf/) संरचना जो वक्र के समाप्ति बिंदु को दर्शाती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

चार [`Point`](../../point/) संरचनाओं द्वारा परिभाषित एक Bézier स्प्लाइन बनाता है।

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) संरचना जो वक्र के रंग, चौड़ाई और शैली को निर्धारित करती है। |
| pt1 | Point | [`Point`](../../point/) संरचना जो वक्र के प्रारंभिक बिंदु को दर्शाती है। |
| pt2 | Point | [`Point`](../../point/) संरचना जो वक्र के पहले नियंत्रण बिंदु को दर्शाती है। |
| pt3 | Point | [`Point`](../../point/) संरचना जो वक्र के दूसरे नियंत्रण बिंदु को दर्शाती है। |
| pt4 | Point | [`Point`](../../point/) संरचना जो वक्र के समाप्ति बिंदु को दर्शाती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


