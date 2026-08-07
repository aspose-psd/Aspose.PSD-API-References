---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आंशिक रूप से लोड किए गए पिक्सेल्स के अनुरूप है."
type: docs
weight: 132
url: /hi/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

आंशिक रूप से लोड किए गए पिक्सेल्स के अनुरूप है.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | लोड किए गए पिक्सेल को प्रोसेस करता है। |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


लोड किए गए पिक्सेल को प्रोसेस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल आयत। |
| pixels | [Color\[\]](../../com.aspose.psd/color) | पिक्सेल। |
| start | [Point](../../com.aspose.psd/point) | शुरुआती पिक्सेल बिंदु। यदि (left,top) के बराबर नहीं है तो इसका मतलब है कि हमारे पास पूर्ण आयत नहीं है। |
| end | [Point](../../com.aspose.psd/point) | अंतिम पिक्सेल बिंदु। यदि (right,bottom) के बराबर नहीं है तो इसका मतलब है कि हमारे पास पूर्ण आयत नहीं है। |

