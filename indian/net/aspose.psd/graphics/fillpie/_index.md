---
title: "Graphics.FillPie"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics विधि। एक RectangleF संरचना और दो रेडियल लाइनों द्वारा परिभाषित दीर्घवृत्त से परिभाषित पाई सेक्शन के आंतरिक भाग को भरती है।"
type: docs
weight: 380
url: /hi/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

एक [`RectangleF`](../../rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त से परिभाषित पाई सेक्शन के आंतरिक भाग को भरती है।

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | Rectangle | [`Rectangle`](../../rectangle/) संरचना जो उस बाउंडिंग आयत को दर्शाती है जो पाई सेक्शन के स्रोत दीर्घवृत्त को परिभाषित करती है। |
| startAngle | Single | कोण डिग्री में, x-अक्ष से पाई सेक्शन की पहली किनारे तक घड़ी की दिशा में मापा गया। |
| sweepAngle | Single | कोण डिग्री में, *startAngle* पैरामीटर से घड़ी की दिशा में मापी गई, पाई सेक्शन की दूसरी ओर तक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

एक [`RectangleF`](../../rectanglef/) संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त से परिभाषित पाई सेक्शन के आंतरिक भाग को भरती है।

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) संरचना जो उस बाउंडिंग आयत को दर्शाती है जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| startAngle | Single | कोण डिग्री में, x-अक्ष से पाई सेक्शन की पहली किनारे तक घड़ी की दिशा में मापा गया। |
| sweepAngle | Single | कोण डिग्री में, *startAngle* पैरामीटर से घड़ी की दिशा में मापी गई, पाई सेक्शन की दूसरी ओर तक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

एक जोड़े निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट एलिप्स से परिभाषित पाई सेक्शन के अंदरूनी भाग को भरता है।

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | Single | उस बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| y | Single | उस बाउंडिंग आयत के ऊपर-बाएँ कोने का y-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| चौड़ाई | Single | उस बाउंडिंग आयत की चौड़ाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| ऊँचाई | Single | उस बाउंडिंग आयत की ऊँचाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| startAngle | Single | कोण डिग्री में, x-अक्ष से पाई सेक्शन की पहली किनारे तक घड़ी की दिशा में मापा गया। |
| sweepAngle | Single | कोण डिग्री में, *startAngle* पैरामीटर से घड़ी की दिशा में मापी गई, पाई सेक्शन की दूसरी ओर तक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

एक जोड़े निर्देशांक, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट एलिप्स से परिभाषित पाई सेक्शन के अंदरूनी भाग को भरता है।

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) जो भराव की विशेषताओं को निर्धारित करता है। |
| x | Int32 | उस बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| y | Int32 | उस बाउंडिंग आयत के ऊपर-बाएँ कोने का y-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| चौड़ाई | Int32 | उस बाउंडिंग आयत की चौड़ाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| ऊँचाई | Int32 | उस बाउंडिंग आयत की ऊँचाई, जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई सेक्शन आता है। |
| startAngle | Int32 | कोण डिग्री में, x-अक्ष से पाई सेक्शन की पहली किनारे तक घड़ी की दिशा में मापा गया। |
| sweepAngle | Int32 | कोण डिग्री में, *startAngle* पैरामीटर से घड़ी की दिशा में मापी गई, पाई सेक्शन की दूसरी ओर तक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *brush* शून्य है। |

### देखें भी

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


