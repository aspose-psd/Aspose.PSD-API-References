---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। Point संरचनाओं की एक सरणी को जोड़ने वाली रेखा खंडों की श्रृंखला बनाता है।"
type: docs
weight: 270
url: /hi/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

एक श्रृंखला रेखा खंडों को खींचता है जो एक सरणी के [`Point`](../../point/) संरचनाओं को जोड़ते हैं।

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो रेखा खंडों का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | Point[] | एक सरणी के [`Point`](../../point/) संरचनाएँ जो जोड़ने के बिंदुओं का प्रतिनिधित्व करती हैं। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |
| ArgumentException | *points* सरणी में 2 से कम बिंदु हैं। |

### देखें भी

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

एक श्रृंखला रेखा खंडों को खींचता है जो एक सरणी के [`PointF`](../../pointf/) संरचनाओं को जोड़ते हैं।

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) जो रेखा खंडों का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | PointF[] | एक सरणी के [`PointF`](../../pointf/) संरचनाएँ जो जोड़ने के बिंदुओं का प्रतिनिधित्व करती हैं। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *pen* शून्य है। -या- *points* शून्य है। |
| ArgumentException | *points* सरणी में 2 से कम बिंदु हैं। |

### देखें भी

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


