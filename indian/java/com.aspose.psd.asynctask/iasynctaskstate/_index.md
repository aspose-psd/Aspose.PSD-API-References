---
title: "IAsyncTaskState"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "असिंक्रोनस कार्य की स्थिति तक पहुँच प्रदान करता है।"
type: docs
weight: 17
url: /hi/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

असिंक्रोनस कार्य की स्थिति तक पहुँच प्रदान करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getProgress()](#getProgress--) | असिंक्रोनस टास्क की प्रगति प्राप्त करता है। |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | प्रगति अधिकतम मान को बढ़ाता है। |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | असिंक्रोनस कार्य की प्रगति सेट करता है। |
| [isCanceled()](#isCanceled--) | एक मान प्राप्त करता है जो दर्शाता है कि असिंक्रोनस कार्य रद्द किया गया है या नहीं। |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


असिंक्रोनस टास्क की प्रगति प्राप्त करता है।

मान: असिंक्रोनस कार्य की प्रगति।

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


प्रगति अधिकतम मान को बढ़ाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | वृद्धि मान। |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


असिंक्रोनस कार्य की प्रगति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | प्रगति स्थिति। |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


एक मान प्राप्त करता है जो दर्शाता है कि असिंक्रोनस कार्य रद्द किया गया है या नहीं।

मान: यदि असिंक्रोनस कार्य रद्द किया गया है तो true; अन्यथा false।

**Returns:**
boolean - एक मान जो दर्शाता है कि असिंक्रोनस कार्य रद्द किया गया है या नहीं।
