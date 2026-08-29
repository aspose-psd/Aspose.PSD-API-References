---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। एक RectangleF संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट एलिप्स द्वारा परिभाषित पाई आकार को ड्रॉ करता है।"
type: docs
weight: 290
url: /hi/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

एक एलिप्स द्वारा परिभाषित पाई आकार को ड्रॉ करता है, जो एक [`RectangleF`](../../rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट है।

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला [`Pen`](../../pen/)। |
| rect | RectangleF | एक [`RectangleF`](../../rectanglef/) संरचना जो उस बाउंडिंग आयत का प्रतिनिधित्व करती है जो एलिप्स को परिभाषित करती है, जिससे पाई आकार आता है। |
| startAngle | Single | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | Single | कोण, डिग्री में मापा गया, *startAngle* पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

एक निर्देशांक युग्म, चौड़ाई, ऊँचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट एक दीर्घवृत्त द्वारा परिभाषित पाई आकार बनाती है।

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला [`Pen`](../../pen/)। |
| x | Single | बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो एलिप्स को परिभाषित करता है, जिससे पाई आकार आता है। |
| y | Single | बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| चौड़ाई | Single | बाउंडिंग आयत की चौड़ाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| ऊँचाई | Single | बाउंडिंग आयत की ऊँचाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| startAngle | Single | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | Single | कोण, डिग्री में मापा गया, *startAngle* पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

एक दीर्घवृत्त द्वारा परिभाषित पाई आकार को बनाता है, जिसे एक [`Rectangle`](../../rectangle/) संरचना और दो रेडियल रेखाओं द्वारा निर्दिष्ट किया गया है।

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला [`Pen`](../../pen/)। |
| rect | Rectangle | [`Rectangle`](../../rectangle/) संरचना जो बाउंडिंग आयत का प्रतिनिधित्व करती है, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| startAngle | Single | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | Single | कोण, डिग्री में मापा गया, *startAngle* पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

एक निर्देशांक युग्म, चौड़ाई, ऊँचाई और दो रेडियल रेखाओं द्वारा निर्दिष्ट एक दीर्घवृत्त द्वारा परिभाषित पाई आकार बनाती है।

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | पाई आकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला [`Pen`](../../pen/)। |
| x | Int32 | बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो एलिप्स को परिभाषित करता है, जिससे पाई आकार आता है। |
| y | Int32 | बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| चौड़ाई | Int32 | बाउंडिंग आयत की चौड़ाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| ऊँचाई | Int32 | बाउंडिंग आयत की ऊँचाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| startAngle | Int32 | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | Int32 | कोण, डिग्री में मापा गया, *startAngle* पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। |

### देखें भी

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


