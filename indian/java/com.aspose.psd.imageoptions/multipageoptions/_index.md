---
title: "MultiPageOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एकाधिक पृष्ठों को सपोर्ट करने वाले फ़ॉर्मेट्स के लिए बेस क्लास।"
type: docs
weight: 17
url: /hi/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

एकाधिक पृष्ठों को सपोर्ट करने वाले फ़ॉर्मेट्स के लिए बेस क्लास।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | एक्सपोर्ट एरिया को प्राप्त करता है या सेट करता है। |
| [getMergeLayers()](#getMergeLayers--) | क्या [merege layers] है, यह दर्शाने वाला मान प्राप्त करता है। |
| [getMode()](#getMode--) | मोड को प्राप्त करता है या सेट करता है। |
| [getOutputLayersNames()](#getOutputLayersNames--) | आउटपुट लेयर नामों को प्राप्त करता है या सेट करता है (यदि निर्यात प्रारूप लेयर नामकरण का समर्थन करता है, उदाहरण के लिए Psd के लिए काम करता है)। |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | पृष्ठ रास्टराइज़ेशन विकल्प प्राप्त करता है। |
| [getPageTitles()](#getPageTitles--) | पृष्ठ शीर्षक प्राप्त करता है या सेट करता है। |
| [getPages()](#getPages--) | पृष्ठों को प्राप्त करता है या सेट करता है। |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | समय अंतराल प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | रेंज एरे से पृष्ठों को प्रारंभ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | एक्सपोर्ट एरिया को प्राप्त करता है या सेट करता है। |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | क्या [merege layers] है, यह दर्शाने वाला मान सेट करता है। |
| [setMode(int value)](#setMode-int-) | मोड को प्राप्त करता है या सेट करता है। |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | आउटपुट लेयर नामों को प्राप्त करता है या सेट करता है (यदि निर्यात प्रारूप लेयर नामकरण का समर्थन करता है, उदाहरण के लिए Psd के लिए काम करता है)। |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | पृष्ठ रास्टराइज़ेशन विकल्प सेट करता है। |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | पृष्ठ शीर्षक प्राप्त करता है या सेट करता है। |
| [setPages(int[] value)](#setPages-int---) | पृष्ठों को प्राप्त करता है या सेट करता है। |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | समय अंतराल सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पृष्ठ | int[] | पृष्ठ। |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पृष्ठ | int[] | पृष्ठों की एरे। |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | निर्यात क्षेत्र। |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageTitles | java.lang.String[] | पृष्ठ शीर्षक। |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageTitles | java.lang.String[] | पृष्ठ शीर्षक। |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | निर्यात क्षेत्र। |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | The IntRange। |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | The IntRange। |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | निर्यात क्षेत्र। |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | The IntRange। |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | The IntRange। |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | निर्यात क्षेत्र। |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पृष्ठ | int | पृष्ठ अनुक्रमांक। |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


MultiPageOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पृष्ठ | int | पृष्ठ अनुक्रमांक। |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | निर्यात क्षेत्र। |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


एक्सपोर्ट एरिया को प्राप्त करता है या सेट करता है।

मान: निर्यात क्षेत्र।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


क्या [merege layers] है, यह दर्शाने वाला मान प्राप्त करता है।

मान: यदि [merege layers] है तो true; अन्यथा false।

**Returns:**
boolean - एक मान जो दर्शाता है कि क्या [merege layers] है।
### getMode() {#getMode--}
```
public int getMode()
```


मोड को प्राप्त करता है या सेट करता है।

मान: मोड।

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


आउटपुट लेयर नामों को प्राप्त करता है या सेट करता है (यदि निर्यात प्रारूप लेयर नामकरण का समर्थन करता है, उदाहरण के लिए Psd के लिए काम करता है)।

मान: आउटपुट लेयर नाम।

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


पृष्ठ रास्टराइज़ेशन विकल्प प्राप्त करता है।

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - पृष्ठ रास्टराइज़ेशन विकल्प.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


पृष्ठ शीर्षक प्राप्त करता है या सेट करता है।

मान: पृष्ठ शीर्षक.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


पृष्ठों को प्राप्त करता है या सेट करता है।

मान: पृष्ठ.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


समय अंतराल प्राप्त करता है।

मान: समय अंतराल.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


रेंज एरे से पृष्ठों को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | सीमाएँ. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


एक्सपोर्ट एरिया को प्राप्त करता है या सेट करता है।

मान: निर्यात क्षेत्र।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


क्या [merege layers] है, यह दर्शाने वाला मान सेट करता है।

मान: यदि [merege layers] है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो संकेत करता है कि [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


मोड को प्राप्त करता है या सेट करता है।

मान: मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


आउटपुट लेयर नामों को प्राप्त करता है या सेट करता है (यदि निर्यात प्रारूप लेयर नामकरण का समर्थन करता है, उदाहरण के लिए Psd के लिए काम करता है)।

मान: आउटपुट लेयर नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


पृष्ठ रास्टराइज़ेशन विकल्प सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | पृष्ठ रास्टराइज़ेशन विकल्प. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


पृष्ठ शीर्षक प्राप्त करता है या सेट करता है।

मान: पृष्ठ शीर्षक.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


पृष्ठों को प्राप्त करता है या सेट करता है।

मान: पृष्ठ.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


समय अंतराल सेट करता है।

मान: समय अंतराल.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | समय अंतराल. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

