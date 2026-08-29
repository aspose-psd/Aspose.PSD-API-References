---
title: "Region"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आयतों और पाथ्स से निर्मित ग्राफ़िक्स आकार के आंतरिक भाग का वर्णन करता है।"
type: docs
weight: 90
url: /hi/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

आयत और पाथ से बनी ग्राफ़िक्स आकृति के अंदरूनी हिस्से का वर्णन करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Region()](#Region--) | एक नया T:Aspose.Imaging.Region प्रारंभ करता है। |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | निर्दिष्ट T:Aspose.Imaging.RectangleF संरचना से एक नया T:Aspose.Imaging.Region प्रारंभ करता है। |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | निर्दिष्ट T:Aspose.Imaging.Rectangle संरचना से एक नया T:Aspose.Imaging.Region प्रारंभ करता है। |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | निर्दिष्ट T:Aspose.Imaging.GraphicsPath के साथ एक नया T:Aspose.Imaging.Region प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | इस com.aspose.psd.Region को अपडेट करके निर्दिष्ट com.aspose.psd.GraphicsPath के उस भाग को शामिल करता है जो इस com.aspose.psd.region के साथ प्रतिच्छेद नहीं करता। |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | इस com.aspose.psd.Region को अपडेट करके निर्दिष्ट com.aspose.psd.Rectangle संरचना के उस भाग को शामिल करता है जो इस com.aspose.psd.region के साथ प्रतिच्छेद नहीं करता। |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह निर्दिष्ट  com.aspose.psd.RectangleF  संरचना का वह भाग शामिल करे जो इस  com.aspose.psd.region  के साथ प्रतिच्छेद नहीं करता है . |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह निर्दिष्ट  com.aspose.psd.Region  का वह भाग शामिल करे जो इस  com.aspose.psd.region  के साथ प्रतिच्छेद नहीं करता है . |
| [deepClone()](#deepClone--) | इस  com.aspose.psd.region  की एक सटीक गहरी प्रतिलिपि बनाता है . |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.graphicsPath  के साथ प्रतिच्छेद नहीं करता है . |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के साथ प्रतिच्छेद नहीं करता है. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के साथ प्रतिच्छेद नहीं करता है. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.region  के साथ प्रतिच्छेद नहीं करता है . |
| [getActions_internalized()](#getActions-internalized--) | क्षेत्र क्रियाओं को प्राप्त करता है. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.graphicsPath  के साथ प्रतिच्छेद में ले सके . |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के साथ प्रतिच्छेद में ले सके. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के साथ प्रतिच्छेद में ले सके. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.region  के साथ प्रतिच्छेद में ले सके . |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | जाँचता है कि यह  com.aspose.psd.Region  निर्दिष्ट ड्राइंग सतह पर खाली आंतरिक भाग रखता है या नहीं. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.Region  इस  com.aspose.psd.Region  के समान है या नहीं निर्दिष्ट ड्राइंग सतह पर. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | जाँचता है कि यह  com.aspose.psd.Region  निर्दिष्ट ड्राइंग सतह पर अनंत आंतरिक भाग रखता है या नहीं. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.Point  संरचना इस  com.aspose.psd.region  के भीतर शामिल है या नहीं . |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.Point  संरचना इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.PointF  संरचना इस  com.aspose.psd.region  के भीतर शामिल है या नहीं . |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.PointF  संरचना इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है . |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.Rectangle  संरचना का कोई भाग इस  com.aspose.psd.region  के भीतर शामिल है या नहीं . |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.Rectangle  संरचना का कोई भाग इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है . |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.RectangleF  संरचना का कोई भाग इस  com.aspose.psd.region  के भीतर शामिल है या नहीं . |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट  com.aspose.psd.RectangleF  संरचना का कोई भाग इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है . |
| [isVisible(float x, float y)](#isVisible-float-float-) | जाँचता है कि निर्दिष्ट बिंदु इस  com.aspose.psd.region  के भीतर शामिल है या नहीं . |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट बिंदु इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है . |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.region  के भीतर सम्मिलित किया गया है या नहीं। |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.Region  में सम्मिलित किया गया है या नहीं, जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग करके चित्रित किया जाता है। |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट बिंदु इस  com.aspose.psd.Region  वस्तु के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट  com.aspose.psd.Graphics  वस्तु का उपयोग करके चित्रित किया जाता है। |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.region  के भीतर सम्मिलित किया गया है या नहीं। |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.Region  में सम्मिलित किया गया है या नहीं, जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग करके चित्रित किया जाता है। |
| [makeEmpty()](#makeEmpty--) | इस  com.aspose.psd.Region  को एक खाली आंतरिक भाग में प्रारंभ करता है। |
| [makeInfinite()](#makeInfinite--) | इस  com.aspose.psd.Region  वस्तु को एक अनंत आंतरिक भाग में प्रारंभ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | परिवर्तन पर क्षेत्र को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | इस  com.aspose.psd.Region  को निर्दिष्ट  com.aspose.psd.matrix  द्वारा रूपांतरित करता है। |
| [translate(float dx, float dy)](#translate-float-float-) | इस  com.aspose.psd.Region  के निर्देशांक को निर्दिष्ट मात्रा से ऑफ़सेट करता है। |
| [translate(int dx, int dy)](#translate-int-int-) | इस  com.aspose.psd.Region  के निर्देशांक को निर्दिष्ट मात्रा से ऑफ़सेट करता है। |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.graphicsPath  के संघ में अपडेट करता है। |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के संघ में अपडेट करता है। |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के संघ में अपडेट करता है। |
| [union(Region region)](#union-com.aspose.psd.Region-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.region  के संघ में अपडेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.graphicsPath  के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.region  के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है। |
### Region() {#Region--}
```
public Region()
```


एक नया T:Aspose.Imaging.Region प्रारंभ करता है।

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


निर्दिष्ट T:Aspose.Imaging.RectangleF संरचना से एक नया T:Aspose.Imaging.Region प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  T:Aspose.Imaging.RectangleF  संरचना जो नए  T:Aspose.Imaging.Region  के आंतरिक भाग को परिभाषित करती है। |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


निर्दिष्ट T:Aspose.Imaging.Rectangle संरचना से एक नया T:Aspose.Imaging.Region प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | एक  T:Aspose.Imaging.Rectangle  संरचना जो नए  T:Aspose.Imaging.Region  के आंतरिक भाग को परिभाषित करती है। |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


निर्दिष्ट T:Aspose.Imaging.GraphicsPath के साथ एक नया T:Aspose.Imaging.Region प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  T:Aspose.Imaging.GraphicsPath  जो नए  T:Aspose.Imaging.Region  को परिभाषित करता है। |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


इस com.aspose.psd.Region को अपडेट करके निर्दिष्ट com.aspose.psd.GraphicsPath के उस भाग को शामिल करता है जो इस com.aspose.psd.region के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | यह  com.aspose.psd.GraphicsPath  इस  com.aspose.psd.region  को पूरक करने के लिए। |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


इस com.aspose.psd.Region को अपडेट करके निर्दिष्ट com.aspose.psd.Rectangle संरचना के उस भाग को शामिल करता है जो इस com.aspose.psd.region के साथ प्रतिच्छेद नहीं करता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | यह  com.aspose.psd.Rectangle  संरचना इस  com.aspose.psd.region  को पूरक करने के लिए। |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह निर्दिष्ट  com.aspose.psd.RectangleF  संरचना का वह भाग शामिल करे जो इस  com.aspose.psd.region  के साथ प्रतिच्छेद नहीं करता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | यह  com.aspose.psd.RectangleF  संरचना इस  com.aspose.psd.region  को पूरक करने के लिए। |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह निर्दिष्ट  com.aspose.psd.Region  का वह भाग शामिल करे जो इस  com.aspose.psd.region  के साथ प्रतिच्छेद नहीं करता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | यह  com.aspose.psd.Region  वस्तु इस  com.aspose.psd.Region  वस्तु को पूरक करने के लिए। |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


इस  com.aspose.psd.region  की एक सटीक गहरी प्रतिलिपि बनाता है .

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.graphicsPath  के साथ प्रतिच्छेद नहीं करता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | यह  com.aspose.psd.GraphicsPath  इस  com.aspose.psd.region  से बाहर करने के लिए। |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के साथ प्रतिच्छेद नहीं करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | यह  com.aspose.psd.Rectangle  संरचना इस  com.aspose.psd.region  से बाहर करने के लिए। |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के साथ प्रतिच्छेद नहीं करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | यह com.aspose.psd.RectangleF संरचना इस com.aspose.psd.region से बाहर करने के लिए है। |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह केवल उसके आंतरिक भाग का वह हिस्सा शामिल करे जो निर्दिष्ट  com.aspose.psd.region  के साथ प्रतिच्छेद नहीं करता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | यह com.aspose.psd.Region इस com.aspose.psd.region से बाहर करने के लिए है। |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


क्षेत्र क्रियाओं को प्राप्त करता है.

**Returns:**
com.aspose.internal.RegionAction[] - क्षेत्र क्रियाएँ।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.graphicsPath  के साथ प्रतिच्छेद में ले सके .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | यह com.aspose.psd.GraphicsPath इस com.aspose.psd.region के साथ प्रतिच्छेद करने के लिए है। |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के साथ प्रतिच्छेद में ले सके.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | यह com.aspose.psd.Rectangle संरचना इस com.aspose.psd.region के साथ प्रतिच्छेद करने के लिए है। |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के साथ प्रतिच्छेद में ले सके.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | यह com.aspose.psd.RectangleF संरचना इस com.aspose.psd.region के साथ प्रतिच्छेद करने के लिए है। |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


इस  com.aspose.psd.Region  को अपडेट करता है ताकि यह स्वयं को निर्दिष्ट  com.aspose.psd.region  के साथ प्रतिच्छेद में ले सके .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | यह com.aspose.psd.Region इस com.aspose.psd.region के साथ प्रतिच्छेद करने के लिए है। |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


जाँचता है कि यह  com.aspose.psd.Region  निर्दिष्ट ड्राइंग सतह पर खाली आंतरिक भाग रखता है या नहीं.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ड्राइंग सतह का प्रतिनिधित्व करता है। |

**Returns:**
boolean - true यदि इस com.aspose.psd.Region का आंतरिक भाग तब खाली हो जाता है जब g के साथ जुड़ी परिवर्तन लागू की जाती है; अन्यथा, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.Region  इस  com.aspose.psd.Region  के समान है या नहीं निर्दिष्ट ड्राइंग सतह पर.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | यह com.aspose.psd.Region परीक्षण के लिए। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ड्राइंग सतह का प्रतिनिधित्व करता है। |

**Returns:**
boolean - True यदि क्षेत्र का आंतरिक भाग इस क्षेत्र के आंतरिक भाग के समान हो जब g पैरामीटर के साथ जुड़ी परिवर्तन लागू की जाती है; अन्यथा, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


जाँचता है कि यह  com.aspose.psd.Region  निर्दिष्ट ड्राइंग सतह पर अनंत आंतरिक भाग रखता है या नहीं.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ड्राइंग सतह का प्रतिनिधित्व करता है। |

**Returns:**
boolean - true यदि इस com.aspose.psd.Region का आंतरिक भाग तब अनंत हो जाता है जब g के साथ जुड़ी परिवर्तन लागू की जाती है; अन्यथा, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.Point  संरचना इस  com.aspose.psd.region  के भीतर शामिल है या नहीं .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह com.aspose.psd.Point संरचना परीक्षण के लिए। |

**Returns:**
boolean - true जब point इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.Point  संरचना इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | यह com.aspose.psd.Point संरचना परीक्षण के लिए। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - true जब point इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.PointF  संरचना इस  com.aspose.psd.region  के भीतर शामिल है या नहीं .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | यह com.aspose.psd.PointF संरचना परीक्षण के लिए। |

**Returns:**
boolean - true जब point इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.PointF  संरचना इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | यह com.aspose.psd.PointF संरचना परीक्षण के लिए। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - true जब point इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.Rectangle  संरचना का कोई भाग इस  com.aspose.psd.region  के भीतर शामिल है या नहीं .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | यह com.aspose.psd.Rectangle संरचना परीक्षण के लिए। |

**Returns:**
boolean - यह विधि true लौटाती है जब rect का कोई भी भाग इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.Rectangle  संरचना का कोई भाग इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | यह com.aspose.psd.Rectangle संरचना परीक्षण के लिए। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - true जब rect का कोई भी भाग इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.RectangleF  संरचना का कोई भाग इस  com.aspose.psd.region  के भीतर शामिल है या नहीं .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | यह com.aspose.psd.RectangleF संरचना परीक्षण के लिए। |

**Returns:**
boolean - true जब rect का कोई भी भाग इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


जाँचता है कि निर्दिष्ट  com.aspose.psd.RectangleF  संरचना का कोई भाग इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | यह com.aspose.psd.RectangleF संरचना परीक्षण के लिए। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - true जब rect इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


जाँचता है कि निर्दिष्ट बिंदु इस  com.aspose.psd.region  के भीतर शामिल है या नहीं .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns:**
boolean - True जब निर्दिष्ट point इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


जाँचता है कि निर्दिष्ट बिंदु इस  com.aspose.psd.Region  के भीतर शामिल है या नहीं जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग किया जाता है .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
boolean - True जब निर्दिष्ट point इस com.aspose.psd.Region के भीतर सम्मिलित हो; अन्यथा, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.region  के भीतर सम्मिलित किया गया है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | परीक्षण के लिए आयत की चौड़ाई। |
| height | float | परीक्षण के लिए आयत की ऊँचाई। |

**Returns:**
बूलियन - सत्य जब निर्दिष्ट आयत का कोई भी भाग इस  com.aspose.psd.Region  वस्तु में सम्मिलित हो; अन्यथा, असत्य।
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.Region  में सम्मिलित किया गया है या नहीं, जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | परीक्षण के लिए आयत की चौड़ाई। |
| height | float | परीक्षण के लिए आयत की ऊँचाई। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
बूलियन - सत्य जब निर्दिष्ट आयत का कोई भी भाग इस  com.aspose.psd.Region  में सम्मिलित हो; अन्यथा, असत्य।
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


जाँचता है कि निर्दिष्ट बिंदु इस  com.aspose.psd.Region  वस्तु के भीतर सम्मिलित है या नहीं, जब निर्दिष्ट  com.aspose.psd.Graphics  वस्तु का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
बूलियन - सत्य जब निर्दिष्ट बिंदु इस  com.aspose.psd.Region  में सम्मिलित हो; अन्यथा, असत्य।
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.region  के भीतर सम्मिलित किया गया है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | परीक्षण के लिए आयत की चौड़ाई। |
| height | int | परीक्षण के लिए आयत की ऊँचाई। |

**Returns:**
बूलियन - सत्य जब निर्दिष्ट आयत का कोई भी भाग इस  com.aspose.psd.Region  में सम्मिलित हो; अन्यथा, असत्य।
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


जाँचता है कि निर्दिष्ट आयत के किसी भी भाग को यह  com.aspose.psd.Region  में सम्मिलित किया गया है या नहीं, जब निर्दिष्ट  com.aspose.psd.graphics  का उपयोग करके चित्रित किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | परीक्षण के लिए आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | परीक्षण के लिए आयत की चौड़ाई। |
| height | int | परीक्षण के लिए आयत की ऊँचाई। |
| g | [Graphics](../../com.aspose.psd/graphics) | एक com.aspose.psd.Graphics जो एक ग्राफ़िक्स संदर्भ का प्रतिनिधित्व करता है। |

**Returns:**
बूलियन - सत्य जब निर्दिष्ट आयत का कोई भी भाग इस  com.aspose.psd.Region  में सम्मिलित हो; अन्यथा, असत्य।
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


इस  com.aspose.psd.Region  को एक खाली आंतरिक भाग में प्रारंभ करता है।

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


इस  com.aspose.psd.Region  वस्तु को एक अनंत आंतरिक भाग में प्रारंभ करता है।

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


परिवर्तन पर क्षेत्र को प्राप्त करता है या सेट करता है।

मान: परिवर्तन पर क्षेत्र।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


इस  com.aspose.psd.Region  को निर्दिष्ट  com.aspose.psd.matrix  द्वारा रूपांतरित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | यह  com.aspose.psd.Matrix  है जिससे इस  com.aspose.psd.region  को रूपांतरित किया जाता है। |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


इस  com.aspose.psd.Region  के निर्देशांक को निर्दिष्ट मात्रा से ऑफ़सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | इस  com.aspose.psd.Region  को क्षैतिज रूप से ऑफसेट करने की मात्रा। |
| dy | float | इस  com.aspose.psd.Region  को लंबवत रूप से ऑफसेट करने की मात्रा। |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


इस  com.aspose.psd.Region  के निर्देशांक को निर्दिष्ट मात्रा से ऑफ़सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | int | इस  com.aspose.psd.Region  को क्षैतिज रूप से ऑफसेट करने की मात्रा। |
| dy | int | इस  com.aspose.psd.Region  को लंबवत रूप से ऑफसेट करने की मात्रा। |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.graphicsPath  के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | इस  com.aspose.psd.region  के साथ मिलाने के लिए  com.aspose.psd.GraphicsPath  । |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | इस  com.aspose.psd.region  के साथ मिलाने के लिए  com.aspose.psd.Rectangle  संरचना। |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | इस  com.aspose.psd.region  के साथ मिलाने के लिए  com.aspose.psd.RectangleF  संरचना। |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.region  के संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | इस  com.aspose.psd.region  के साथ मिलाने के लिए  com.aspose.psd.Region  । |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.graphicsPath  के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | इस  com.aspose.psd.region  के साथ XOR करने के लिए  com.aspose.psd.GraphicsPath  । |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.Rectangle  संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | इस  com.aspose.psd.region  के साथ XOR करने के लिए  com.aspose.psd.Rectangle  संरचना। |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.RectangleF  संरचना के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | इस  com.aspose.psd.region  के साथ XOR करने के लिए  com.aspose.psd.RectangleF  संरचना। |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


इस  com.aspose.psd.Region  को स्वयं और निर्दिष्ट  com.aspose.psd.region  के प्रतिच्छेदन को घटाकर संघ में अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | इस  com.aspose.psd.region  के साथ XOR करने के लिए  com.aspose.psd.Region  । |

