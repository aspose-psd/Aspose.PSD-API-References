---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट अंडाकार के एक भाग को दर्शाने वाला आर्क ड्रॉ करता है।"
type: docs
weight: 170
url: /hi/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

एक आर्क ड्रॉ करता है जो एक अंडाकार के उस हिस्से को दर्शाता है जिसे निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट किया गया है।

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आर्क के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x | Single | एलिप्स को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | Single | एलिप्स को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | Single | एलिप्स को परिभाषित करने वाले आयत की चौड़ाई। |
| ऊँचाई | Single | एलिप्स को परिभाषित करने वाले आयत की ऊँचाई। |
| startAngle | Single | x-अक्ष से आर्क के प्रारंभिक बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |
| sweepAngle | Single | *startAngle* पैरामीटर से आर्क के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

एक [`RectangleF`](../../rectanglef/) संरचना द्वारा निर्दिष्ट एलिप्स के एक भाग को दर्शाने वाला आर्क बनाता है।

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आर्क के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |
| startAngle | Single | x-अक्ष से आर्क के प्रारंभिक बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |
| sweepAngle | Single | *startAngle* पैरामीटर से आर्क के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है |

### देखें भी

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

एक आर्क ड्रॉ करता है जो एक अंडाकार के उस हिस्से को दर्शाता है जिसे निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट किया गया है।

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आर्क के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| x | Int32 | एलिप्स को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | Int32 | एलिप्स को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | Int32 | एलिप्स को परिभाषित करने वाले आयत की चौड़ाई। |
| ऊँचाई | Int32 | एलिप्स को परिभाषित करने वाले आयत की ऊँचाई। |
| startAngle | Int32 | x-अक्ष से आर्क के प्रारंभिक बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |
| sweepAngle | Int32 | *startAngle* पैरामीटर से आर्क के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

एक [`Rectangle`](../../rectangle/) संरचना द्वारा निर्दिष्ट एलिप्स के एक भाग को दर्शाने वाला आर्क बनाता है।

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो आर्क के रंग, चौड़ाई और शैली को निर्धारित करता है। |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |
| startAngle | Single | x-अक्ष से आर्क के प्रारंभिक बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |
| sweepAngle | Single | *startAngle* पैरामीटर से आर्क के समाप्ति बिंदु तक घड़ी की दिशा में मापा गया कोण (डिग्री में)। |

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


