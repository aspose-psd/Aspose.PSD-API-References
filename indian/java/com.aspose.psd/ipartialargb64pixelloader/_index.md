---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "64-बिट ARGB पिक्सेल्स लोडर."
type: docs
weight: 131
url: /hi/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64-बिट ARGB पिक्सेल्स लोडर.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | लोड किए गए पिक्सेल को प्रोसेस करता है। |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


लोड किए गए पिक्सेल को प्रोसेस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल आयत। |
| पिक्सेल | long[] | 64-बिट ARGB पिक्सेल। |
| start | [Point](../../com.aspose.psd/point) | शुरुआती पिक्सेल बिंदु। यदि (left,top) के बराबर नहीं है तो इसका मतलब है कि हमारे पास पूर्ण आयत नहीं है। |
| end | [Point](../../com.aspose.psd/point) | अंतिम पिक्सेल बिंदु। यदि (right,bottom) के बराबर नहीं है तो इसका मतलब है कि हमारे पास पूर्ण आयत नहीं है। |

