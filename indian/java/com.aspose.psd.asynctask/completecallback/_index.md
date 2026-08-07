---
title: "CompleteCallback"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "कार्य पूर्णता इवेंट प्राप्त करने के लिए कॉलबैक फ़ंक्शन।"
type: docs
weight: 15
url: /hi/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

कार्य पूर्णता इवेंट प्राप्त करने के लिए कॉलबैक फ़ंक्शन।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | कार्य पूर्णता इवेंट प्राप्त करने के लिए कॉलबैक फ़ंक्शन। |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


कार्य पूर्णता इवेंट प्राप्त करने के लिए कॉलबैक फ़ंक्शन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | असिंक्रोनस कार्य। |
| wasCancelled | boolean | यदि सेट किया गया हो  true  [was cancelled]. |
| त्रुटि | java.lang.Throwable | त्रुटि। |

