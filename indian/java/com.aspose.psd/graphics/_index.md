---
title: "Graphics"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "वर्तमान असेंबली में उपयोग किए गए ग्राफिक्स इंजन के अनुसार ग्राफिक्स का प्रतिनिधित्व करता है।"
type: docs
weight: 49
url: /hi/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

वर्तमान असेंबली में उपयोग किए गए ग्राफिक्स इंजन के अनुसार ग्राफिक्स का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Graphics वर्ग की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | बोल्ड टेक्स्ट शैली आकार गुणांक प्राप्त करता है |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | इटैलिक टेक्स्ट शैली आकार गुणांक प्राप्त करता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | प्रभाव लागू करता है। |
| [beginUpdate()](#beginUpdate--) | निम्नलिखित ग्राफ़िक्स ऑपरेशन्स की कैशिंग शुरू करता है। |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | निर्दिष्ट रंग का उपयोग करके ग्राफ़िक्स सतह को साफ़ करता है। |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | एक आर्क बनाता है जो एक  Rectangle  संरचना द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है। |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | एक आर्क बनाता है जो एक  RectangleF  संरचना द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है। |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | एक आर्क बनाता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है। |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | एक आर्क बनाता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है। |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | चार  Point  संरचनाओं द्वारा परिभाषित बीज़र स्प्लाइन बनाता है। |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | चार  PointF  संरचनाओं द्वारा परिभाषित बीज़र स्प्लाइन बनाता है। |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | चार क्रमबद्ध निर्देशांक युग्मों द्वारा परिभाषित Bézier स्प्लाइन को खींचता है जो बिंदुओं का प्रतिनिधित्व करते हैं। |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | एक  PointF  सरणी से Bézier स्प्लाइनों की श्रृंखला को खींचता है। |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | एक  Point  सरणी से Bézier स्प्लाइनों की श्रृंखला को खींचता है। |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | एक  PointF  संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को खींचता है। |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | एक निर्दिष्ट तनाव का उपयोग करके,  PointF  संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को खींचता है। |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | एक  Point  संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को खींचता है। |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | एक निर्दिष्ट तनाव का उपयोग करके,  Point  संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | एक निर्दिष्ट  PointF  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  PointF  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | एक निर्दिष्ट  PointF  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  PointF  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | एक निर्दिष्ट  Point  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  Point  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  Point  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है। |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | एक बाउंडिंग  Rectangle  संरचना द्वारा निर्दिष्ट एलिप्स को खींचता है। |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | एक बाउंडिंग  RectangleF  द्वारा परिभाषित एलिप्स को खींचता है। |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | एक बाउंडिंग आयत द्वारा परिभाषित एलिप्स को खींचता है, जो एक निर्देशांक युग्म, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है। |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | एक बाउंडिंग आयत द्वारा परिभाषित एलिप्स को खींचता है, जो एक निर्देशांक युग्म, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है। |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | निर्दिष्ट  Image  को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | निर्दिष्ट  Image  को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | निर्दिष्ट  Image  को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है। |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर खींचता है। |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है। |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | एक निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर खींचता है। |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | एक निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर खींचता है। |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर खींचता है। |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | एक निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर खींचता है। |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | निर्दिष्ट image को बिना स्केलिंग के खींचता है और आवश्यक होने पर उसे क्लिप करता है, ताकि वह निर्दिष्ट आयत में फिट हो सके। |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | दो  Point  संरचनाओं को जोड़ती हुई रेखा को खींचता है। |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | दो  PointF  संरचनाओं को जोड़ती हुई रेखा को खींचता है। |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा को खींचता है। |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा को खींचता है। |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | एक  PointF  संरचनाओं की सरणी को जोड़ने वाले रेखा खंडों की श्रृंखला को खींचता है। |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | एक श्रृंखला के रेखा खंड बनाता है जो  Point  संरचनाओं की एक array को जोड़ते हैं। |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | एक  com.aspose.psd.graphicsPath  बनाता है। |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | एक पाई आकार बनाता है जो एक  Rectangle  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है। |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | एक पाई आकार बनाता है जो एक  RectangleF  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है। |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | एक पाई आकार बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, ऊँचाई, और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है। |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | एक पाई आकार बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, ऊँचाई, और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है। |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | एक बहुभुज बनाता है जो  PointF  संरचनाओं की एक array द्वारा परिभाषित होता है। |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | एक बहुभुज बनाता है जो  Point  संरचनाओं की एक array द्वारा परिभाषित होता है। |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | एक आयत बनाता है जो  Rectangle  संरचना द्वारा निर्दिष्ट है। |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | एक आयत बनाता है जो  RectangleF  संरचना द्वारा निर्दिष्ट है। |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | एक आयत बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, और ऊँचाई द्वारा निर्दिष्ट है। |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | एक आयत बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, और ऊँचाई द्वारा निर्दिष्ट है। |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | एक श्रृंखला के आयत बनाता है जो  RectangleF  संरचनाओं द्वारा निर्दिष्ट हैं। |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | एक श्रृंखला के आयत बनाता है जो  Rectangle  संरचनाओं द्वारा निर्दिष्ट हैं। |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है। |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है। |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है। |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है। |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है। |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है। |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | निर्दिष्ट आयत में Adobe-संगत तरीके से निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है। |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | निर्दिष्ट स्थान पर Adobe-संगत तरीके से निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है। |
| [endUpdate()](#endUpdate--) | BeginUpdate को कॉल करने के बाद शुरू किए गए ग्राफ़िक्स ऑपरेशनों की कैशिंग समाप्त करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.PointF  संरचनाओं की एक array द्वारा परिभाषित है। |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.PointF  संरचनाओं की एक array द्वारा परिभाषित है, निर्दिष्ट fill mode का उपयोग करके। |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.PointF  संरचनाओं की एक array द्वारा परिभाषित है, निर्दिष्ट fill mode और tension का उपयोग करके। |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.Point  संरचनाओं की एक array द्वारा परिभाषित है। |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.Point  संरचनाओं की एक array द्वारा परिभाषित है, निर्दिष्ट fill mode का उपयोग करके। |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.Point  संरचनाओं की एक array द्वारा परिभाषित है, निर्दिष्ट fill mode और tension का उपयोग करके। |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.Rectangle  संरचना द्वारा निर्दिष्ट है। |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.RectangleF  संरचना द्वारा निर्दिष्ट है। |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | एक  com.aspose.psd.graphicsPath  के आंतरिक भाग को भरता है। |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | एक पाई सेक्शन के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.RectangleF  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है। |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | एक पाई सेक्शन के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.RectangleF  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है। |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | एक पाई सेक्शन के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है। |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | एक पाई सेक्शन के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है। |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.PointF  संरचनाओं की एक एरे और  FillMode.Alternate  द्वारा निर्दिष्ट बिंदुओं द्वारा परिभाषित है। |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.PointF  संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं को निर्दिष्ट फ़िल मोड का उपयोग करके परिभाषित करता है। |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.Point  संरचनाओं की एरे और  FillMode.Alternate  द्वारा निर्दिष्ट बिंदुओं द्वारा परिभाषित है। |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.Point  संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं को निर्दिष्ट फ़िल मोड का उपयोग करके परिभाषित करता है। |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | एक  Rectangle  संरचना द्वारा निर्दिष्ट आयत के आंतरिक भाग को भरता है। |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | एक  RectangleF  संरचना द्वारा निर्दिष्ट आयत के आंतरिक भाग को भरता है। |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | एक आयत के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | एक आयत के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है। |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | एक श्रृंखला के आयतों के आंतरिक भागों को भरता है, जो  RectangleF  संरचनाओं द्वारा निर्दिष्ट हैं। |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | एक श्रृंखला के आयतों के आंतरिक भागों को भरता है, जो  Rectangle  संरचनाओं द्वारा निर्दिष्ट हैं। |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | एक  com.aspose.psd.region  के आंतरिक भाग को भरता है। |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | क्लिप क्षेत्र को प्राप्त करता है या सेट करता है। |
| [getCompositingQuality()](#getCompositingQuality--) | कॉम्पोज़िटिंग क्वालिटी को प्राप्त करता है या सेट करता है। |
| [getDpiX()](#getDpiX--) | इस com.aspose.psd.graphics की क्षैतिज रिज़ॉल्यूशन को प्राप्त करता है। |
| [getDpiY()](#getDpiY--) | इस com.aspose.psd.graphics की लंबवत रिज़ॉल्यूशन को प्राप्त करता है। |
| [getImage()](#getImage--) | छवि को प्राप्त करता है। |
| [getInterpolationMode()](#getInterpolationMode--) | इंटरपोलेशन मोड को प्राप्त करता है या सेट करता है। |
| [getPageScale()](#getPageScale--) | इस com.aspose.psd.graphics के लिए विश्व इकाइयों और पेज इकाइयों के बीच स्केलिंग को प्राप्त करता है या सेट करता है। |
| [getPageUnit()](#getPageUnit--) | इस com.aspose.psd.graphics में पेज निर्देशांक के लिए उपयोग की जाने वाली माप इकाई को प्राप्त करता है या सेट करता है। |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | छवि विकल्पों को प्राप्त करता है या सेट करता है, जिसका उपयोग ड्रॉ करने के लिए पेंटेबल vactor छवियों को बनाने में किया जाता है। |
| [getSmoothingMode()](#getSmoothingMode--) | स्मूदिंग मोड को प्राप्त करता है या सेट करता है। |
| [getTextRenderingHint()](#getTextRenderingHint--) | टेक्स्ट रेंडरिंग हिंट को प्राप्त करता है या सेट करता है। |
| [getTransform()](#getTransform--) | इस com.aspose.psd.graphics के लिए ज्यामितीय विश्व परिवर्तन की एक प्रति को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | एक मान प्राप्त करता है जो दर्शाता है कि ग्राफ़िक्स BeginUpdate कॉल स्थिति में है या नहीं। |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | स्ट्रिंग को [GraphicsPath](../../com.aspose.psd/graphicspath) क्लास का उपयोग करके मापता है। |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | स्ट्रिंग को मापता है। |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | निर्दिष्ट पैरामीटर के साथ निर्दिष्ट टेक्स्ट स्ट्रिंग को मापता है। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | इस com.aspose.psd.Graphics के स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को दर्शाने वाले com.aspose.psd.Matrix को निर्दिष्ट com.aspose.psd.Matrix से पूर्व में निर्दिष्ट com.aspose.psd.matrix को जोड़कर गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | इस com.aspose.psd.Graphics के स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को दर्शाने वाले com.aspose.psd.Matrix को निर्दिष्ट क्रम में निर्दिष्ट com.aspose.psd.Matrix से गुणा करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | com.aspose.psd.graphics.Transform प्रॉपर्टी को पहचान (identity) पर रीसेट करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | क्लिप क्षेत्र को प्राप्त करता है या सेट करता है। |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | कॉम्पोज़िटिंग क्वालिटी को प्राप्त करता है या सेट करता है। |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | इंटरपोलेशन मोड को प्राप्त करता है या सेट करता है। |
| [setPageScale(float value)](#setPageScale-float-) | इस com.aspose.psd.graphics के लिए विश्व इकाइयों और पेज इकाइयों के बीच स्केलिंग को प्राप्त करता है या सेट करता है। |
| [setPageUnit(int value)](#setPageUnit-int-) | इस com.aspose.psd.graphics में पेज निर्देशांक के लिए उपयोग की जाने वाली माप इकाई को प्राप्त करता है या सेट करता है। |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | छवि विकल्पों को प्राप्त करता है या सेट करता है, जिसका उपयोग ड्रॉ करने के लिए पेंटेबल vactor छवियों को बनाने में किया जाता है। |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | स्मूदिंग मोड को प्राप्त करता है या सेट करता है। |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | टेक्स्ट रेंडरिंग हिंट को प्राप्त करता है या सेट करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | इस com.aspose.psd.graphics के लिए ज्यामितीय विश्व परिवर्तन की एक प्रति को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Graphics वर्ग की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | स्रोत छवि। |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


बोल्ड टेक्स्ट शैली आकार गुणांक प्राप्त करता है

जादूई संख्याओं का उपयोग किया जा रहा है क्योंकि GDI हमेशा केवल रेगुलर शैली के लिए माप प्रदान करता है।

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


इटैलिक टेक्स्ट शैली आकार गुणांक प्राप्त करता है

जादूई संख्याओं का उपयोग किया जा रहा है क्योंकि GDI हमेशा केवल रेगुलर शैली के लिए माप प्रदान करता है।

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


प्रभाव लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इफ़ेक्ट | com.aspose.internal.IEffect | लागू करने के लिए इफ़ेक्ट। |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


निम्नलिखित ग्राफ़िक्स ऑपरेशनों की कैशिंग शुरू करता है। बाद में लागू किए गए ग्राफ़िक्स इफ़ेक्ट तुरंत लागू नहीं होंगे, बल्कि End Update सभी इफ़ेक्ट को एक साथ लागू करेगा।

ध्यान दें कि BeginUpdate कॉल होने के बाद के इफ़ेक्ट तब लागू नहीं होंगे जब EndUpdate कॉल नहीं किया गया हो।

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


निर्दिष्ट रंग का उपयोग करके ग्राफ़िक्स सतह को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | ग्राफ़िक्स सतह को साफ़ करने के लिए रंग। |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


एक आर्क बनाता है जो एक  Rectangle  संरचना द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | पेन जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | RectangleF संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |
| startAngle | float | कोण (डिग्री में) जो x-अक्ष से घड़ी की दिशा में आर्क के प्रारंभिक बिंदु तक मापा जाता है। |
| sweepAngle | float | कोण (डिग्री में) जो  startAngle  पैरामीटर से घड़ी की दिशा में आर्क के समाप्ति बिंदु तक मापा जाता है। |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


एक आर्क बनाता है जो एक  RectangleF  संरचना द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | पेन जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |
| startAngle | float | कोण (डिग्री में) जो x-अक्ष से घड़ी की दिशा में आर्क के प्रारंभिक बिंदु तक मापा जाता है। |
| sweepAngle | float | कोण (डिग्री में) जो  startAngle  पैरामीटर से घड़ी की दिशा में आर्क के समाप्ति बिंदु तक मापा जाता है। |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


एक आर्क बनाता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | पेन जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | float | दीर्घवृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | वृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | float | वृत्त को परिभाषित करने वाले आयत की चौड़ाई। |
| height | float | वृत्त को परिभाषित करने वाले आयत की ऊँचाई। |
| startAngle | float | कोण (डिग्री में) जो x-अक्ष से घड़ी की दिशा में आर्क के प्रारंभिक बिंदु तक मापा जाता है। |
| sweepAngle | float | कोण (डिग्री में) जो  startAngle  पैरामीटर से घड़ी की दिशा में आर्क के समाप्ति बिंदु तक मापा जाता है। |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


एक आर्क बनाता है जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट दीर्घवृत्त के भाग को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | पेन जो आर्क का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | int | दीर्घवृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | वृत्त को परिभाषित करने वाले आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | int | वृत्त को परिभाषित करने वाले आयत की चौड़ाई। |
| height | int | वृत्त को परिभाषित करने वाले आयत की ऊँचाई। |
| startAngle | int | कोण (डिग्री में) जो x-अक्ष से घड़ी की दिशा में आर्क के प्रारंभिक बिंदु तक मापा जाता है। |
| sweepAngle | int | कोण (डिग्री में) जो  startAngle  पैरामीटर से घड़ी की दिशा में आर्क के समाप्ति बिंदु तक मापा जाता है। |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


चार  Point  संरचनाओं द्वारा परिभाषित बीज़र स्प्लाइन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  संरचना जो वक्र का रंग, चौड़ाई और शैली निर्धारित करती है। |
| pt1 | [Point](../../com.aspose.psd/point) | Point  संरचना जो वक्र के प्रारंभिक बिंदु को दर्शाती है। |
| pt2 | [Point](../../com.aspose.psd/point) | Point  संरचना जो वक्र के पहले नियंत्रण बिंदु को दर्शाती है। |
| pt3 | [Point](../../com.aspose.psd/point) | Point  संरचना जो वक्र के दूसरे नियंत्रण बिंदु को दर्शाती है। |
| pt4 | [Point](../../com.aspose.psd/point) | Point  संरचना जो वक्र के समाप्ति बिंदु को दर्शाती है। |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


चार  PointF  संरचनाओं द्वारा परिभाषित बीज़र स्प्लाइन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो वक्र के प्रारंभिक बिंदु को दर्शाती है। |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो वक्र के पहले नियंत्रण बिंदु को दर्शाती है। |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो वक्र के दूसरे नियंत्रण बिंदु को दर्शाती है। |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो वक्र के समाप्ति बिंदु को दर्शाती है। |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


चार क्रमबद्ध निर्देशांक युग्मों द्वारा परिभाषित Bézier स्प्लाइन को खींचता है जो बिंदुओं का प्रतिनिधित्व करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x1 | float | वक्र के प्रारंभिक बिंदु का x-निर्देशांक। |
| y1 | float | वक्र के प्रारंभिक बिंदु का y-निर्देशांक। |
| x2 | float | वक्र के पहले नियंत्रण बिंदु का x-निर्देशांक। |
| y2 | float | वक्र के पहले नियंत्रण बिंदु का y-निर्देशांक। |
| x3 | float | वक्र के दूसरे नियंत्रण बिंदु का x-निर्देशांक। |
| y3 | float | वक्र के दूसरे नियंत्रण बिंदु का y-निर्देशांक। |
| x4 | float | वक्र के समाप्ति बिंदु का x-निर्देशांक। |
| y4 | float | वक्र के समाप्ति बिंदु का y-निर्देशांक। |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


एक  PointF  सरणी से Bézier स्प्लाइनों की श्रृंखला को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | वक्र को निर्धारित करने वाले बिंदुओं को दर्शाने वाले PointF संरचनाओं की सरणी। |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


एक  Point  सरणी से Bézier स्प्लाइनों की श्रृंखला को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो वक्र का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | वक्र को निर्धारित करने वाले बिंदुओं को दर्शाने वाले Point संरचनाओं की सरणी। |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


PointF संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को बनाता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव और FillMode.Alternate भराव मोड का उपयोग करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले PointF संरचनाओं की सरणी। |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


निर्दिष्ट तनाव का उपयोग करके PointF संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को बनाता है। यह विधि डिफ़ॉल्ट FillMode.Alternate भराव मोड का उपयोग करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले PointF संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Point संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को बनाता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव और FillMode.Alternate भराव मोड का उपयोग करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [Point\[\]](../../com.aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले Point संरचनाओं की सरणी। |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


निर्दिष्ट तनाव का उपयोग करके Point संरचनाओं की सरणी द्वारा परिभाषित बंद कार्डिनल स्प्लाइन को बनाता है। यह विधि डिफ़ॉल्ट FillMode.Alternate भराव मोड का उपयोग करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [Point\[\]](../../com.aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले Point संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


निर्दिष्ट PointF संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को बनाता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले PointF संरचनाओं की सरणी। |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  PointF  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | वक्र को परिभाषित करने वाले बिंदुओं को दर्शाने वाले PointF संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


निर्दिष्ट PointF संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को बनाता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है। यह विधि 0.5 की डिफ़ॉल्ट तनाव का उपयोग करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले PointF संरचनाओं की सरणी। |
| ऑफ़सेट | int | बिंदु पैरामीटर की सरणी के पहले तत्व से वक्र के प्रारंभिक बिंदु तक का ऑफ़सेट। |
| numberOfSegments | int | वक्र में शामिल करने के लिए प्रारंभिक बिंदु के बाद के खंडों की संख्या। |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


निर्दिष्ट तनाव का उपयोग करके निर्दिष्ट PointF संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को बनाता है। चित्रण सरणी की शुरुआत से ऑफ़सेट होकर शुरू होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | स्प्लाइन को परिभाषित करने वाले PointF संरचनाओं की सरणी। |
| ऑफ़सेट | int | बिंदु पैरामीटर की सरणी के पहले तत्व से वक्र के प्रारंभिक बिंदु तक का ऑफ़सेट। |
| numberOfSegments | int | वक्र में शामिल करने के लिए प्रारंभिक बिंदु के बाद के खंडों की संख्या। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


एक निर्दिष्ट  Point  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [Point\[\]](../../com.aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले Point संरचनाओं की सरणी। |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  Point  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [Point\[\]](../../com.aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले Point संरचनाओं की सरणी। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


एक निर्दिष्ट तनाव का उपयोग करके, एक निर्दिष्ट  Point  संरचनाओं की सरणी के माध्यम से कार्डिनल स्प्लाइन को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | वक्र के रंग, चौड़ाई और ऊँचाई को निर्धारित करने वाला Pen। |
| points | [Point\[\]](../../com.aspose.psd/point) | स्प्लाइन को परिभाषित करने वाले Point संरचनाओं की सरणी। |
| ऑफ़सेट | int | बिंदु पैरामीटर की सरणी के पहले तत्व से वक्र के प्रारंभिक बिंदु तक का ऑफ़सेट। |
| numberOfSegments | int | वक्र में शामिल करने के लिए प्रारंभिक बिंदु के बाद के खंडों की संख्या। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


एक बाउंडिंग  Rectangle  संरचना द्वारा निर्दिष्ट एलिप्स को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | अण्डाकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला Pen। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | अण्डाकार की सीमाओं को परिभाषित करने वाली Rectangle संरचना। |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


एक बाउंडिंग  RectangleF  द्वारा परिभाषित एलिप्स को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | अण्डाकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला Pen। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF संरचना जो दीर्घवृत्त की सीमाओं को परिभाषित करती है। |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


एक बाउंडिंग आयत द्वारा परिभाषित एलिप्स को खींचता है, जो एक निर्देशांक युग्म, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | अण्डाकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला Pen। |
| x | float | अण्डाकार को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | float | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


एक बाउंडिंग आयत द्वारा परिभाषित एलिप्स को खींचता है, जो एक निर्देशांक युग्म, ऊँचाई और चौड़ाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | अण्डाकार के रंग, चौड़ाई और शैली को निर्धारित करने वाला Pen। |
| x | int | अण्डाकार को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | int | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


निर्दिष्ट  Image  को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| point | [Point](../../com.aspose.psd/point) | Point  संरचना जो ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का स्थान दर्शाती है। |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


निर्दिष्ट  Image  को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| point | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो ड्रॉ की गई छवि के ऊपरी-बाएँ कोने को दर्शाती है। |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | स्रोत आयत। |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | स्रोत आयत। |
| srcUnit | int | माप की इकाइयाँ। |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | स्रोत आयत। |
| srcUnit | int | माप की इकाइयाँ। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | छवि विशेषताएँ। |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | स्रोत आयत। |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | स्रोत आयत। |
| srcUnit | int | माप की इकाइयाँ। |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


निर्दिष्ट  image  का निर्दिष्ट भाग को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | ड्रॉ करने के लिए छवि। |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | तीन PointF संरचनाओं की एरे जो एक समानांतर चतुर्भुज को परिभाषित करती हैं। |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | स्रोत आयत। |
| srcUnit | int | माप की इकाइयाँ। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | छवि विशेषताएँ। |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  संरचना जो ड्रॉ की गई छवि का स्थान और आकार निर्दिष्ट करती है। |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | rect स्रोत। |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | rect गंतव्य। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | rect स्रोत। |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | rect गंतव्य। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | छवि विशेषताएँ। |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य आयत। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य आयत। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | छवि विशेषताएँ। |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  संरचना जो ड्रॉ की गई छवि का स्थान और आकार निर्दिष्ट करती है। |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | rect स्रोत। |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | rect गंतव्य। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | स्रोत आयत। |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | गंतव्य आयत। |
| graphicsUnit | int | उपयोग करने के लिए ग्राफ़िक्स इकाई। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | उपयोग करने के लिए छवि विशेषताएँ। |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | गंतव्य आयत। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | ड्रॉ करने के लिए गंतव्य आयत। |
| graphicsUnit | int | ग्राफ़िक्स इकाई। |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | छवि विशेषताएँ। |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


निर्दिष्ट  Image  को, उसके मूल भौतिक आकार का उपयोग करके, निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| x | float | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| x | float | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | ड्रॉ की गई छवि की चौड़ाई। |
| height | float | खींची गई छवि की ऊँचाई। |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| x | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


निर्दिष्ट  Image  को, निर्दिष्ट स्थान पर और निर्दिष्ट आकार के साथ खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| x | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | ड्रॉ की गई छवि की चौड़ाई। |
| height | int | खींची गई छवि की ऊँचाई। |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


एक निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| point | [Point](../../com.aspose.psd/point) | Point  संरचना जो खींची गई छवि के ऊपर-बाएँ कोने को निर्दिष्ट करती है। |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


एक निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  जो खींची गई छवि के ऊपर-बाएँ कोने को निर्दिष्ट करता है। आयत की X और Y गुण ऊपर-बाएँ कोने को निर्दिष्ट करते हैं। Width और Height गुणों को अनदेखा किया जाता है। |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्देशांक युग्म द्वारा निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| x | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


एक निर्दिष्ट image को, उसके मूल भौतिक आकार का उपयोग करके, एक निर्दिष्ट स्थान पर खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| x | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | ड्रॉ की गई छवि के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | पैरामीटर का उपयोग नहीं किया गया है। |
| height | int | पैरामीटर का उपयोग नहीं किया गया है। |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


निर्दिष्ट image को बिना स्केलिंग के खींचता है और आवश्यक होने पर उसे क्लिप करता है, ताकि वह निर्दिष्ट आयत में फिट हो सके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | जिस छवि को ड्रॉ करना है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | वह  Rectangle  जिसमें छवि को खींचा जाता है। |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


दो  Point  संरचनाओं को जोड़ती हुई रेखा को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो रेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| point1 | [Point](../../com.aspose.psd/point) | Point  संरचना जो कनेक्ट करने के लिए पहला बिंदु दर्शाती है। |
| point2 | [Point](../../com.aspose.psd/point) | Point  संरचना जो कनेक्ट करने के लिए दूसरा बिंदु दर्शाती है। |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


दो  PointF  संरचनाओं को जोड़ती हुई रेखा को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो रेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| point1 | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो कनेक्ट करने के लिए पहला बिंदु दर्शाती है। |
| point2 | [PointF](../../com.aspose.psd/pointf) | PointF  संरचना जो कनेक्ट करने के लिए दूसरा बिंदु दर्शाती है। |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो रेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x1 | float | पहले बिंदु का x-निर्देशांक। |
| y1 | float | पहले बिंदु का y-निर्देशांक। |
| x2 | float | दूसरे बिंदु का x-निर्देशांक। |
| y2 | float | दूसरे बिंदु का y-निर्देशांक। |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


निर्दिष्ट निर्देशांक युग्मों द्वारा निर्दिष्ट दो बिंदुओं को जोड़ती हुई रेखा को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो रेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x1 | int | पहले बिंदु का x-निर्देशांक। |
| y1 | int | पहले बिंदु का y-निर्देशांक। |
| x2 | int | दूसरे बिंदु का x-निर्देशांक। |
| y2 | int | दूसरे बिंदु का y-निर्देशांक। |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


एक  PointF  संरचनाओं की सरणी को जोड़ने वाले रेखा खंडों की श्रृंखला को खींचता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो रेखा खंडों का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | PointF  संरचनाओं की एरे जो कनेक्ट करने वाले बिंदुओं को दर्शाती है। |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


एक श्रृंखला के रेखा खंड बनाता है जो  Point  संरचनाओं की एक array को जोड़ते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो रेखा खंडों का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | Point  संरचनाओं की एरे जो कनेक्ट करने वाले बिंदुओं को दर्शाती है। |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


एक  com.aspose.psd.graphicsPath  बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen  जो पथ का रंग, चौड़ाई और शैली निर्धारित करता है। |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  ड्रॉ करने के लिए। |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


एक पाई आकार बनाता है जो एक  Rectangle  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो पाई आकार का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  संरचना जो बाउंडिंग आयत को दर्शाती है जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| startAngle | float | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | float | कोण, डिग्री में मापा गया,  startAngle  पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


एक पाई आकार बनाता है जो एक  RectangleF  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो पाई आकार का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  संरचना जो बाउंडिंग आयत को दर्शाती है जो उस दीर्घवृत्त को परिभाषित करती है जिससे पाई आकार आता है। |
| startAngle | float | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | float | कोण, डिग्री में मापा गया,  startAngle  पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


एक पाई आकार बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, ऊँचाई, और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो पाई आकार का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | float | बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| y | float | बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| width | float | बाउंडिंग आयत की चौड़ाई, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| height | float | बाउंडिंग आयत की ऊँचाई, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| startAngle | float | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | float | कोण, डिग्री में मापा गया,  startAngle  पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


एक पाई आकार बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, ऊँचाई, और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  जो पाई आकार का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | int | बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| y | int | बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| width | int | बाउंडिंग आयत की चौड़ाई, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| height | int | बाउंडिंग आयत की ऊँचाई, जो उस दीर्घवृत्त को परिभाषित करता है जिससे पाई आकार आता है। |
| startAngle | int | कोण, डिग्री में मापा गया, x-अक्ष से पाई आकार की पहली किनारे तक घड़ी की दिशा में। |
| sweepAngle | int | कोण, डिग्री में मापा गया,  startAngle  पैरामीटर से पाई आकार की दूसरी किनारे तक घड़ी की दिशा में। |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


एक बहुभुज बनाता है जो  PointF  संरचनाओं की एक array द्वारा परिभाषित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen जो बहुभुज का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | PointF संरचनाओं की Array जो बहुभुज के शीर्ष बिंदुओं का प्रतिनिधित्व करती है। |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


एक बहुभुज बनाता है जो  Point  संरचनाओं की एक array द्वारा परिभाषित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen जो बहुभुज का रंग, चौड़ाई और शैली निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | Point संरचनाओं की Array जो बहुभुज के शीर्ष बिंदुओं का प्रतिनिधित्व करती है। |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


एक आयत बनाता है जो  Rectangle  संरचना द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | एक Pen जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | एक Rectangle संरचना जो ड्रॉ करने के लिए आयत का प्रतिनिधित्व करती है। |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


एक आयत बनाता है जो  RectangleF  संरचना द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | एक Pen जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | एक RectangleF संरचना जो ड्रॉ करने के लिए आयत का प्रतिनिधित्व करती है। |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


एक आयत बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | एक Pen जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | float | ड्रॉ करने के लिए आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ करने के लिए आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | ड्रॉ करने के लिए आयत की चौड़ाई। |
| height | float | ड्रॉ करने के लिए आयत की ऊँचाई। |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


एक आयत बनाता है जो एक निर्देशांक जोड़ी, चौड़ाई, और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen जो आयत का रंग, चौड़ाई और शैली निर्धारित करता है। |
| x | int | ड्रॉ करने के लिए आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | int | ड्रॉ करने के लिए आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | ड्रॉ करने के लिए आयत की चौड़ाई। |
| height | int | ड्रॉ करने के लिए आयत की ऊँचाई। |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


एक श्रृंखला के आयत बनाता है जो  RectangleF  संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen जो आयतों की रूपरेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | RectangleF संरचनाओं की Array जो ड्रॉ करने के लिए आयतों का प्रतिनिधित्व करती है। |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


एक श्रृंखला के आयत बनाता है जो  Rectangle  संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen जो आयतों की रूपरेखा का रंग, चौड़ाई और शैली निर्धारित करता है। |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Rectangle संरचनाओं की Array जो ड्रॉ करने के लिए आयतों का प्रतिनिधित्व करती है। |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF संरचना जो ड्रॉ किए गए पाठ के ऊपरी-बाएँ कोने को निर्दिष्ट करती है। |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF संरचना जो ड्रॉ किए गए पाठ के ऊपरी-बाएँ कोने को निर्दिष्ट करती है। |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए पाठ पर लागू होते हैं। |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  संरचना जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करती है। |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


निर्दिष्ट आयत में निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  संरचना जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करती है। |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए पाठ पर लागू होते हैं। |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| x | float | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| x | float | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए पाठ पर लागू होते हैं। |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


निर्दिष्ट आयत में Adobe-संगत तरीके से निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है, जिसमें निर्दिष्ट  com.aspose.psd.stringFormat  के स्वरूपण गुणों का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  संरचना जो ड्रॉ किए गए टेक्स्ट का स्थान निर्दिष्ट करती है। |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat जो फ़ॉर्मेटिंग गुणों को निर्दिष्ट करता है, जैसे लाइन स्पेसिंग और संरेखण, जो ड्रॉ किए गए पाठ पर लागू होते हैं। |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


निर्दिष्ट स्थान पर Adobe-संगत तरीके से निर्दिष्ट पाठ स्ट्रिंग को निर्दिष्ट  com.aspose.psd.Brush  और  com.aspose.psd.Font  वस्तुओं के साथ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| s | java.lang.String | ड्रॉ करने के लिए स्ट्रिंग। |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font जो स्ट्रिंग के पाठ प्रारूप को परिभाषित करता है। |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush जो ड्रॉ किए गए पाठ का रंग और बनावट निर्धारित करता है। |
| x | float | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | ड्रॉ किए गए टेक्स्ट के ऊपरी-बाएँ कोने का y-निर्देशांक। |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


BeginUpdate को कॉल करने के बाद शुरू किए गए ग्राफ़िक्स ऑपरेशनों की कैशिंग समाप्त करता है। पूर्ववर्ती ग्राफ़िक्स ऑपरेशनों को इस मेथड को कॉल करने पर एक साथ लागू किया जाएगा।

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
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो com.aspose.psd.PointF संरचनाओं की एरे द्वारा परिभाषित है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 और  FillMode.Alternate  फ़िल मोड का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | com.aspose.psd.PointF संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो com.aspose.psd.PointF संरचनाओं की एरे द्वारा परिभाषित है, निर्दिष्ट फ़िल मोड का उपयोग करते हुए। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | com.aspose.psd.PointF संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | int | com.aspose.psd.FillMode एनेमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.PointF  संरचनाओं की एक array द्वारा परिभाषित है, निर्दिष्ट fill mode और tension का उपयोग करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | एक com.aspose.psd.Brush जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | com.aspose.psd.PointF संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | int | com.aspose.psd.FillMode एनेमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो com.aspose.psd.Point संरचनाओं की एरे द्वारा परिभाषित है। यह मेथड डिफ़ॉल्ट टेंशन 0.5 और  FillMode.Alternate  फ़िल मोड का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | com.aspose.psd.Point संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


एक बंद कार्डिनल स्प्लाइन कर्व के अंदरूनी भाग को भरता है जो com.aspose.psd.Point संरचनाओं की एरे द्वारा परिभाषित है, निर्दिष्ट फ़िल मोड का उपयोग करते हुए। यह मेथड डिफ़ॉल्ट टेंशन 0.5 का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | com.aspose.psd.Point संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | int | com.aspose.psd.FillMode एनेमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


एक बंद कार्डिनल स्प्लाइन कर्व के अंदर को भरता है जो  com.aspose.psd.Point  संरचनाओं की एक array द्वारा परिभाषित है, निर्दिष्ट fill mode और tension का उपयोग करके।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | com.aspose.psd.Point संरचनाओं की एरे जो स्प्लाइन को परिभाषित करती है। |
| fillmode | int | com.aspose.psd.FillMode एनेमरेशन का सदस्य जो निर्धारित करता है कि कर्व कैसे भरा जाता है। |
| तनाव | float | वक्र के तनाव को निर्दिष्ट करने वाला 0.0F या उससे बड़ा मान। |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.Rectangle  संरचना द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle  संरचना जो उस बाउंडिंग रेक्टैंगल को दर्शाती है जो अंडाकार को परिभाषित करता है। |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.RectangleF  संरचना द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  संरचना जो उस बाउंडिंग रेक्टैंगल को दर्शाती है जो अंडाकार को परिभाषित करता है। |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| x | float | अण्डाकार को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | float | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


एक बाउंडिंग आयत द्वारा परिभाषित दीर्घवृत्त के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| x | int | अण्डाकार को परिभाषित करने वाले बाउंडिंग आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | int | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की चौड़ाई। |
| height | int | एलिप्स को परिभाषित करने वाले बाउंडिंग आयत की ऊँचाई। |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


एक  com.aspose.psd.graphicsPath  के आंतरिक भाग को भरता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath  जो भरने के पथ को दर्शाता है। |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


एक पाई सेक्शन के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.RectangleF  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle  संरचना जो उस बाउंडिंग रेक्टैंगल को दर्शाती है जो उस अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| startAngle | float | डिग्री में कोण, जो x-अक्ष से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की पहली किनारे तक। |
| sweepAngle | float | डिग्री में कोण, जो  startAngle  पैरामीटर से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की दूसरी किनारे तक। |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


एक पाई सेक्शन के आंतरिक भाग को भरता है, जो एक  com.aspose.psd.RectangleF  संरचना और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF  संरचना जो उस बाउंडिंग रेक्टैंगल को दर्शाती है जो उस अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| startAngle | float | डिग्री में कोण, जो x-अक्ष से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की पहली किनारे तक। |
| sweepAngle | float | डिग्री में कोण, जो  startAngle  पैरामीटर से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की दूसरी किनारे तक। |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


एक पाई सेक्शन के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| x | float | उस बाउंडिंग रेक्टैंगल के ऊपरी-बाएँ कोने का x-निर्देशांक जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| y | float | उस बाउंडिंग रेक्टैंगल के ऊपरी-बाएँ कोने का y-निर्देशांक जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| width | float | उस बाउंडिंग रेक्टैंगल की चौड़ाई जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| height | float | उस बाउंडिंग रेक्टैंगल की ऊँचाई जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| startAngle | float | डिग्री में कोण, जो x-अक्ष से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की पहली किनारे तक। |
| sweepAngle | float | डिग्री में कोण, जो  startAngle  पैरामीटर से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की दूसरी किनारे तक। |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


एक पाई सेक्शन के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई, ऊँचाई और दो रेडियल लाइनों द्वारा निर्दिष्ट दीर्घवृत्त द्वारा परिभाषित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| x | int | उस बाउंडिंग रेक्टैंगल के ऊपरी-बाएँ कोने का x-निर्देशांक जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| y | int | उस बाउंडिंग रेक्टैंगल के ऊपरी-बाएँ कोने का y-निर्देशांक जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| width | int | उस बाउंडिंग रेक्टैंगल की चौड़ाई जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| height | int | उस बाउंडिंग रेक्टैंगल की ऊँचाई जो अंडाकार को परिभाषित करता है जिससे पाई सेक्शन आता है। |
| startAngle | int | डिग्री में कोण, जो x-अक्ष से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की पहली किनारे तक। |
| sweepAngle | int | डिग्री में कोण, जो  startAngle  पैरामीटर से घड़ी की दिशा में मापा जाता है, पाई सेक्शन की दूसरी किनारे तक। |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.PointF  संरचनाओं की एक एरे और  FillMode.Alternate  द्वारा निर्दिष्ट बिंदुओं द्वारा परिभाषित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | भरण के लिए बहुभुज के शीर्ष बिंदुओं का प्रतिनिधित्व करने वाली  com.aspose.psd.PointF  संरचनाओं की सरणी। |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.PointF  संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं को निर्दिष्ट फ़िल मोड का उपयोग करके परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | भरण के लिए बहुभुज के शीर्ष बिंदुओं का प्रतिनिधित्व करने वाली  com.aspose.psd.PointF  संरचनाओं की सरणी। |
| fillMode | int | भरण की शैली निर्धारित करने वाले  com.aspose.psd.FillMode  एन्यूमरेशन का सदस्य। |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.Point  संरचनाओं की एरे और  FillMode.Alternate  द्वारा निर्दिष्ट बिंदुओं द्वारा परिभाषित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | भरण के लिए बहुभुज के शीर्ष बिंदुओं का प्रतिनिधित्व करने वाली  com.aspose.psd.Point  संरचनाओं की सरणी। |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


एक पॉलीगॉन के आंतरिक भाग को भरता है, जो  com.aspose.psd.Point  संरचनाओं की एरे द्वारा निर्दिष्ट बिंदुओं को निर्दिष्ट फ़िल मोड का उपयोग करके परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| points | [Point\[\]](../../com.aspose.psd/point) | भरण के लिए बहुभुज के शीर्ष बिंदुओं का प्रतिनिधित्व करने वाली  com.aspose.psd.Point  संरचनाओं की सरणी। |
| fillMode | int | भरण की शैली निर्धारित करने वाले  com.aspose.psd.FillMode  एन्यूमरेशन का सदस्य। |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


एक  Rectangle  संरचना द्वारा निर्दिष्ट आयत के आंतरिक भाग को भरता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला ब्रश। |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | भरण के लिए आयत का प्रतिनिधित्व करने वाली  Rectangle  संरचना। |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


एक  RectangleF  संरचना द्वारा निर्दिष्ट आयत के आंतरिक भाग को भरता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला ब्रश। |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | भरण के लिए आयत का प्रतिनिधित्व करने वाली  RectangleF  संरचना। |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


एक आयत के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला ब्रश। |
| x | float | भरण के लिए आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | float | भरण के लिए आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | float | भरण के लिए आयत की चौड़ाई। |
| height | float | भरण के लिए आयत की ऊँचाई। |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


एक आयत के आंतरिक भाग को भरता है, जो निर्देशांक की जोड़ी, चौड़ाई और ऊँचाई द्वारा निर्दिष्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला ब्रश। |
| x | int | भरण के लिए आयत के ऊपर-बाएँ कोने का x-निर्देशांक। |
| y | int | भरण के लिए आयत के ऊपर-बाएँ कोने का y-निर्देशांक। |
| width | int | भरण के लिए आयत की चौड़ाई। |
| height | int | भरण के लिए आयत की ऊँचाई। |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


एक श्रृंखला के आयतों के आंतरिक भागों को भरता है, जो  RectangleF  संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला ब्रश। |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | भरण के लिए आयतों का प्रतिनिधित्व करने वाली  Rectangle  संरचनाओं की सरणी। |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


एक श्रृंखला के आयतों के आंतरिक भागों को भरता है, जो  Rectangle  संरचनाओं द्वारा निर्दिष्ट हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | भरण की विशेषताओं को निर्धारित करने वाला ब्रश। |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | भरण के लिए आयतों का प्रतिनिधित्व करने वाली  Rectangle  संरचनाओं की सरणी। |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


एक  com.aspose.psd.region  के आंतरिक भाग को भरता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  जो फ़िल की विशेषताओं को निर्धारित करता है। |
| region | [Region](../../com.aspose.psd/region) | भरण के लिए क्षेत्र का प्रतिनिधित्व करने वाला  com.aspose.psd.Region। |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


क्लिप क्षेत्र को प्राप्त करता है या सेट करता है।

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


कॉम्पोज़िटिंग क्वालिटी को प्राप्त करता है या सेट करता है।

**Returns:**
int - संयोजन गुणवत्ता।
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


इस com.aspose.psd.graphics की क्षैतिज रिज़ॉल्यूशन को प्राप्त करता है।

**Returns:**
float - इस  com.aspose.psd.graphics  द्वारा समर्थित क्षैतिज रिज़ॉल्यूशन के लिए डॉट्स प्रति इंच में मान।
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


इस com.aspose.psd.graphics की लंबवत रिज़ॉल्यूशन को प्राप्त करता है।

**Returns:**
float - इस  com.aspose.psd.graphics  द्वारा समर्थित लंबवत रिज़ॉल्यूशन के लिए डॉट्स प्रति इंच में मान।
### getImage() {#getImage--}
```
public Image getImage()
```


छवि को प्राप्त करता है।

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


इंटरपोलेशन मोड को प्राप्त करता है या सेट करता है।

**Returns:**
int - इंटरपोलेशन मोड।
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


इस com.aspose.psd.graphics के लिए विश्व इकाइयों और पेज इकाइयों के बीच स्केलिंग को प्राप्त करता है या सेट करता है।

**Returns:**
float - इस  com.aspose.psd.graphics  के लिए विश्व इकाइयों और पृष्ठ इकाइयों के बीच स्केलिंग।
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


इस com.aspose.psd.graphics में पेज निर्देशांक के लिए उपयोग की जाने वाली माप इकाई को प्राप्त करता है या सेट करता है।

**Returns:**
int - इस  com.aspose.psd.graphics  में पृष्ठ निर्देशांक के लिए उपयोग की जाने वाली माप इकाई।
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


छवि विकल्पों को प्राप्त करता है या सेट करता है, जिसका उपयोग ड्रॉ करने के लिए पेंटेबल vactor छवियों को बनाने में किया जाता है।

मान: ड्रॉ करने के लिए पेंटेबल वेक्टर छवियों को बनाने हेतु उपयोग किए जाने वाले इमेज विकल्प।

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


स्मूदिंग मोड को प्राप्त करता है या सेट करता है।

**Returns:**
int - स्मूदिंग मोड।
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


टेक्स्ट रेंडरिंग हिंट को प्राप्त करता है या सेट करता है।

**Returns:**
int - टेक्स्ट रेंडरिंग संकेत।
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


इस com.aspose.psd.graphics के लिए ज्यामितीय विश्व परिवर्तन की एक प्रति को प्राप्त करता है या सेट करता है।

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


एक मान प्राप्त करता है जो दर्शाता है कि ग्राफ़िक्स BeginUpdate कॉल स्थिति में है या नहीं।

**Returns:**
boolean - यदि ग्राफ़िक्स BeginUpdate कॉल स्थिति में है तो  True ; अन्यथा  false ।
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


स्ट्रिंग को [GraphicsPath](../../com.aspose.psd/graphicspath) क्लास का उपयोग करके मापता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | फ़ॉन्ट। |
| पाठ | java.lang.String | पाठ। |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


स्ट्रिंग को मापता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | फ़ॉन्ट। |
|  | पाठ | java.lang.String | पाठ। |

--------------------

GDI परिणाम लगभग हमेशा इटैलिक के लिए मान्य नहीं होता और अक्सर बोल्ड शैलियों के लिए भी मान्य नहीं होता। |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


निर्दिष्ट पैरामीटर के साथ निर्दिष्ट टेक्स्ट स्ट्रिंग को मापता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | मापने के लिए पाठ। |
| font | [Font](../../com.aspose.psd/font) | मापने के लिए फ़ॉन्ट। |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | लेआउट क्षेत्र। |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | स्ट्रिंग फ़ॉर्मेट। |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | निजी फ़ॉन्ट कैश प्राप्त करें। |
| useMagicNumbersForStyles | boolean | यदि सेट किया गया हो  true  [use magic numbers for styles]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


इस com.aspose.psd.Graphics के स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को दर्शाने वाले com.aspose.psd.Matrix को निर्दिष्ट com.aspose.psd.Matrix से पूर्व में निर्दिष्ट com.aspose.psd.matrix को जोड़कर गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ज्यामितीय ट्रांसफ़ॉर्म को गुणा करने के लिए  com.aspose.psd.Matrix  । |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


इस com.aspose.psd.Graphics के स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को दर्शाने वाले com.aspose.psd.Matrix को निर्दिष्ट क्रम में निर्दिष्ट com.aspose.psd.Matrix से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ज्यामितीय ट्रांसफ़ॉर्म को गुणा करने के लिए  com.aspose.psd.Matrix  । |
| order | int | एक  com.aspose.psd.MatrixOrder  जो दो मैट्रिसेज़ को किस क्रम में गुणा किया जाए, निर्दिष्ट करता है। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


com.aspose.psd.graphics.Transform प्रॉपर्टी को पहचान (identity) पर रीसेट करता है।

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। यह विधि घुमाव को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |
| order | int | एक  com.aspose.psd.MatrixOrder  जो घूर्णन मैट्रिक्स को जोड़ना या पहले लगाना है, यह निर्दिष्ट करता है। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। यह विधि स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| order | int | एक  com.aspose.psd.MatrixOrder  जो स्केलिंग मैट्रिक्स को जोड़ना या पहले लगाना है, यह निर्दिष्ट करता है। |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


क्लिप क्षेत्र को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | क्लिप क्षेत्र। |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


कॉम्पोज़िटिंग क्वालिटी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | संयोजन गुणवत्ता। |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


इंटरपोलेशन मोड को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इंटरपोलेशन मोड। |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


इस com.aspose.psd.graphics के लिए विश्व इकाइयों और पेज इकाइयों के बीच स्केलिंग को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस com.aspose.psd.graphics के लिए विश्व इकाइयों और पृष्ठ इकाइयों के बीच स्केलिंग। |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


इस com.aspose.psd.graphics में पेज निर्देशांक के लिए उपयोग की जाने वाली माप इकाई को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस com.aspose.psd.graphics में पृष्ठ निर्देशांक के लिए उपयोग की जाने वाली माप इकाई। |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


छवि विकल्पों को प्राप्त करता है या सेट करता है, जिसका उपयोग ड्रॉ करने के लिए पेंटेबल vactor छवियों को बनाने में किया जाता है।

मान: ड्रॉ करने के लिए पेंटेबल वेक्टर छवियों को बनाने हेतु उपयोग किए जाने वाले इमेज विकल्प।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


स्मूदिंग मोड को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | स्मूदिंग मोड। |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


टेक्स्ट रेंडरिंग हिंट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | टेक्स्ट रेंडरिंग संकेत। |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


इस com.aspose.psd.graphics के लिए ज्यामितीय विश्व परिवर्तन की एक प्रति को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | एक कॉपी  com.aspose.psd.Matrix  की जो इस  com.aspose.psd.graphics  के लिए ज्यामितीय विश्व परिवर्तन को दर्शाती है। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। यह विधि अनुवाद को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |
| order | int | अनुवाद लागू करने का क्रम (पहले जोड़ना या बाद में जोड़ना)। |

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

