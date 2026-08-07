---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "रास्टर इमेज कच्चा डेटा लोडर।"
type: docs
weight: 137
url: /hi/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

रास्टर इमेज कच्चा डेटा लोडर।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। |
| [isRawDataAvailable()](#isRawDataAvailable--) | कच्चा डेटा लोडिंग समर्थित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | कच्चा डेटा लोड करता है। |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है।

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


कच्चा डेटा लोडिंग समर्थित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
बूलियन - यदि कच्चा डेटा लोडिंग समर्थित है तो true; अन्यथा false।
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


कच्चा डेटा लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | कच्चा डेटा लोड करने के लिए आयत। |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | लोड किए गए डेटा के लिए उपयोग करने की कच्चा डेटा सेटिंग्स। नोट: यदि डेटा निर्दिष्ट प्रारूप में नहीं है तो डेटा रूपांतरण किया जाएगा। |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | कच्चा डेटा लोडर। |

