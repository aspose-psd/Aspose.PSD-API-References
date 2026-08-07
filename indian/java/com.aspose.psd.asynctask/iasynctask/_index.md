---
title: "IAsyncTask"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "असिंक्रोनस कार्य।"
type: docs
weight: 16
url: /hi/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

असिंक्रोनस कार्य।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [abort()](#abort--) | इस कार्य को रोकता है। |
| [cancel()](#cancel--) | इस कार्य को रद्द करता है। |
| [getError()](#getError--) | कार्य पूर्ण होने के बाद उपलब्ध कार्य त्रुटि प्राप्त करता है। |
| [getProgressEventHandler()](#getProgressEventHandler--) | असिंक्रोनस कार्य के प्रगति इवेंट हैंडलर को प्राप्त करता है। |
| [getResult()](#getResult--) | इस कार्य का परिणाम प्राप्त करता है। |
| [isBusy()](#isBusy--) | एक मान प्राप्त करता है जो दर्शाता है कि यह कार्य वर्तमान में चल रहा है या नहीं। |
| [isCanceled()](#isCanceled--) | एक मान प्राप्त करता है जो दर्शाता है कि यह कार्य रद्द किया गया था या नहीं। |
| [isFaulted()](#isFaulted--) | एक मान प्राप्त करता है जो दर्शाता है कि यह कार्य त्रुटिपूर्ण था या नहीं। |
| [runAsync()](#runAsync--) | इस कार्य को चलाता है। |
| [runAsync(int priority)](#runAsync-int-) | इस कार्य को चलाता है। |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | पूर्ण कॉलबैक डेलीगेट सेट करता है। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | असिंक्रोनस कार्य के प्रगति इवेंट हैंडलर को सेट करता है। |
### abort() {#abort--}
```
public abstract void abort()
```


इस कार्य को रोकता है। कार्य तुरंत पूरा हो जाता है, लेकिन आंतरिक अनमैनेज्ड संसाधनों को मुक्त न करने का जोखिम रहता है।

### cancel() {#cancel--}
```
public abstract void cancel()
```


इस कार्य को रद्द करता है। कार्य एल्गोरिदम को नियंत्रित रूप से रोककर सुरक्षित रूप से पूरा हो जाता है।

### getError() {#getError--}
```
public abstract Throwable getError()
```


कार्य पूर्ण होने के बाद उपलब्ध कार्य त्रुटि प्राप्त करता है।

मान: कार्य त्रुटि।

**Returns:**
java.lang.Throwable - कार्य त्रुटि जो कार्य पूर्ण होने के बाद उपलब्ध होती है।
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


असिंक्रोनस कार्य के प्रगति इवेंट हैंडलर को प्राप्त करता है।

मान: असिंक्रोनस कार्य का प्रगति इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


इस कार्य का परिणाम प्राप्त करता है।

मान: इस कार्य का परिणाम।

**Returns:**
java.lang.Object - इस कार्य का परिणाम।
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह कार्य वर्तमान में चल रहा है या नहीं।

मान:  true  यदि यह कार्य वर्तमान में चल रहा है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि यह कार्य वर्तमान में चल रहा है या नहीं।
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह कार्य रद्द किया गया था या नहीं।

मान:  true  यदि यह कार्य रद्द किया गया था; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि यह कार्य रद्द किया गया था या नहीं।
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह कार्य त्रुटिपूर्ण था या नहीं।

मान:  true  यदि यह कार्य त्रुटिपूर्ण था; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि यह कार्य त्रुटिपूर्ण था या नहीं।
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


इस कार्य को चलाता है।

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


इस कार्य को चलाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्राथमिकता | int | थ्रेड की प्राथमिकता। |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


पूर्ण कॉलबैक डेलीगेट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | पूर्ण कॉलबैक। |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


असिंक्रोनस कार्य के प्रगति इवेंट हैंडलर को सेट करता है।

मान: असिंक्रोनस कार्य का प्रगति इवेंट हैंडलर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | असिंक्रोनस कार्य का प्रगति इवेंट हैंडलर। |

