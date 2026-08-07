---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आंशिक रूप से लोड किए गए 32-बिट ARGB पिक्सेल्स के अनुरूप है."
type: docs
weight: 130
url: /hi/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

आंशिक रूप से लोड किए गए 32-बिट ARGB पिक्सेल्स के अनुरूप है.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | लोड किए गए पिक्सेल को प्रोसेस करता है। |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


लोड किए गए पिक्सेल को प्रोसेस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल आयत। |
| पिक्सेल | int[] | ARGB प्रारूप में पिक्सेल |
| start | [Point](../../com.aspose.psd/point) | शुरुआती पिक्सेल बिंदु। यदि (left,top) के बराबर नहीं है तो इसका मतलब है कि हमारे पास पूर्ण आयत नहीं है। |
| end | [Point](../../com.aspose.psd/point) | अंतिम पिक्सेल बिंदु। यदि (right,bottom) के बराबर नहीं है तो इसका मतलब है कि हमारे पास पूर्ण आयत नहीं है। |

