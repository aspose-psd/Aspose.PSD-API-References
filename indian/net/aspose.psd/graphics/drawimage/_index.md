---
title: "Graphics.DrawImage"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Graphics मेथड। निर्दिष्ट स्थान पर मूल भौतिक आकार का उपयोग करके निर्दिष्ट Image को खींचता है।"
type: docs
weight: 230
url: /hi/net/aspose.psd/graphics/drawimage/
---
{{< psd/tize >}}
## DrawImage(Image, PointF) {#drawimage_1}

निर्दिष्ट स्थान पर, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, PointF point)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| point | PointF | `[`PointF`](../../pointf/)` संरचना जो खींची गई छवि के ऊपर-बाएँ कोने का प्रतिनिधित्व करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float) {#drawimage_22}

निर्दिष्ट स्थान पर, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, float x, float y)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| x | Single | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Single | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF) {#drawimage_15}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, RectangleF rect)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rect | RectangleF | `[`RectangleF`](../../rectanglef/)` संरचना जो खींची गई छवि के स्थान और आकार को निर्दिष्ट करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit) {#drawimage_11}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectDestination | Rectangle | गंतव्य आयत। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit) {#drawimage_16}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectDestination | RectangleF | गंतव्य आयत। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_12}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectDestination | Rectangle | गंतव्य आयत। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |
| imageAttributes | ImageAttributes | छवि विशेषताएँ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_17}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectDestination | RectangleF | ड्रॉ करने के लिए गंतव्य आयत। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |
| imageAttributes | ImageAttributes | छवि विशेषताएँ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit) {#drawimage_13}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectSource | Rectangle | आयत स्रोत। |
| rectDestination | Rectangle | आयत गंतव्य। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit) {#drawimage_18}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectSource | RectangleF | आयत स्रोत। |
| rectDestination | RectangleF | आयत गंतव्य। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_14}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectSource | Rectangle | आयत स्रोत। |
| rectDestination | Rectangle | आयत गंतव्य। |
| graphicsUnit | GraphicsUnit | ग्राफ़िक्स इकाई। |
| imageAttributes | ImageAttributes | छवि विशेषताएँ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_19}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rectSource | RectangleF | स्रोत आयत। |
| rectDestination | RectangleF | गंतव्य आयत। |
| graphicsUnit | GraphicsUnit | उपयोग करने के लिए ग्राफ़िक्स इकाई। |
| imageAttributes | ImageAttributes | उपयोग करने के लिए छवि विशेषताएँ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[]) {#drawimage_6}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, Point[] destPoints)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | Point[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |

### देखें भी

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle) {#drawimage_7}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | Point[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |
| srcRect | Rectangle | स्रोत आयत। |

### देखें भी

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit) {#drawimage_8}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | Point[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |
| srcRect | Rectangle | स्रोत आयत। |
| srcUnit | GraphicsUnit | माप की इकाइयाँ। |

### देखें भी

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_9}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | Point[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |
| srcRect | Rectangle | स्रोत आयत। |
| srcUnit | GraphicsUnit | माप की इकाइयाँ। |
| imageAttributes | ImageAttributes | छवि विशेषताएँ। |

### देखें भी

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[]) {#drawimage_2}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, PointF[] destPoints)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | PointF[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | छवि |

### देखें भी

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF) {#drawimage_3}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | PointF[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |
| srcRect | RectangleF | स्रोत आयत। |

### देखें भी

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit) {#drawimage_4}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | PointF[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |
| srcRect | RectangleF | स्रोत आयत। |
| srcUnit | GraphicsUnit | माप की इकाइयाँ। |

### देखें भी

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_5}

निर्दिष्ट *image* के निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ बनाता है।

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| छवि | छवि | ड्रॉ करने के लिए छवि। |
| destPoints | PointF[] | तीन PointF संरचनाओं की एक सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है। |
| srcRect | RectangleF | स्रोत आयत। |
| srcUnit | GraphicsUnit | माप की इकाइयाँ। |
| imageAttributes | ImageAttributes | छवि विशेषताएँ। |

### देखें भी

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float, float, float) {#drawimage_23}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, float x, float y, float width, float height)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| x | Single | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Single | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | Single | ड्रॉ की गई छवि की चौड़ाई। |
| ऊँचाई | Single | ड्रॉ की गई छवि की ऊँचाई। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point) {#drawimage}

निर्दिष्ट स्थान पर, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, Point point)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| point | Point | [`Point`](../../point/) संरचना जो ड्रॉ की गई छवि के ऊपरी-बाएँ कोने के स्थान का प्रतिनिधित्व करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int) {#drawimage_20}

निर्दिष्ट छवि को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर बनाता है।

```csharp
public void DrawImage(Image sourceImage, int x, int y)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| x | Int32 | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Int32 | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle) {#drawimage_10}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, Rectangle rect)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| rect | Rectangle | [`Rectangle`](../../rectangle/) संरचना जो ड्रॉ की गई छवि के स्थान और आकार को निर्दिष्ट करती है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int, int, int) {#drawimage_21}

निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ निर्दिष्ट [`Image`](../image/) को खींचता है।

```csharp
public void DrawImage(Image sourceImage, int x, int y, int width, int height)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sourceImage | छवि | खींचने के लिए छवि। |
| x | Int32 | खींची गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | Int32 | खींची गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| चौड़ाई | Int32 | ड्रॉ की गई छवि की चौड़ाई। |
| ऊँचाई | Int32 | ड्रॉ की गई छवि की ऊँचाई। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *sourceImage* शून्य है। |

### देखें भी

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


