---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आंशिक डेटा लोडर."
type: docs
weight: 133
url: /hi/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

आंशिक डेटा लोडर.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | लोड किए गए डेटा को प्रोसेस करता है। |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | लोड किए गए डेटा को प्रोसेस करता है। |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


लोड किए गए डेटा को प्रोसेस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | डेटा आयत। |
| डेटा | byte[] | कच्चा डेटा। |
| start | [Point](../../com.aspose.psd/point) | शुरुआती डेटा बिंदु। यदि (left,top) के बराबर नहीं है, तो इसका अर्थ है कि यह पूर्ण आयत नहीं है। |
| end | [Point](../../com.aspose.psd/point) | अंतिम डेटा बिंदु। यदि (right,bottom) के बराबर नहीं है, तो इसका अर्थ है कि यह पूर्ण आयत नहीं है। |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


लोड किए गए डेटा को प्रोसेस करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | डेटा आयत। |
| डेटा | byte[] | कच्चा डेटा। |
| start | [Point](../../com.aspose.psd/point) | शुरुआती डेटा बिंदु। यदि (left,top) के बराबर नहीं है, तो इसका अर्थ है कि यह पूर्ण आयत नहीं है। |
| end | [Point](../../com.aspose.psd/point) | अंतिम डेटा बिंदु। यदि (right,bottom) के बराबर नहीं है, तो इसका अर्थ है कि यह पूर्ण आयत नहीं है। |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | लोड विकल्प। |

