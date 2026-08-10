---
title: "इंटरफ़ेस IAsyncTask"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.AsyncTask.IAsyncTask इंटरफ़ेस। असिंक्रोनस टास्क"
type: docs
weight: 80
url: /hi/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

असिंक्रोनस टास्क।

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | टास्क पूर्ण होने के बाद उपलब्ध टास्क त्रुटि प्राप्त करता है। |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह टास्क वर्तमान में चल रहा है या नहीं। |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह टास्क रद्द किया गया था या नहीं। |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह टास्क त्रुटिपूर्ण था या नहीं। |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | असिंक्रोनस टास्क की प्रोग्रेस प्राप्त करता है। |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | इस कार्य का परिणाम प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | इस कार्य को समाप्त करता है। कार्य तुरंत पूरा हो जाता है, लेकिन आंतरिक अप्रबंधित संसाधनों को मुक्त न करने का जोखिम रहता है। |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | इस कार्य को रद्द करता है। कार्य एल्गोरिदम को नियंत्रित रूप से रोककर सुरक्षित रूप से पूरा किया जाता है। |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | इस कार्य को चलाता है। |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | इस कार्य को चलाता है। |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | पूर्ण कॉलबैक डेलीगेट सेट करता है। |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | प्रगति कॉलबैक डेलीगेट सेट करता है। |

### देखें भी

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


