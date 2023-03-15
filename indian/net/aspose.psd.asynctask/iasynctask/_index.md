---
title: Interface IAsyncTask
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.AsyncTask.IAsyncTask इंटरफेस. अतुल्यकलक कर्य
type: docs
weight: 80
url: /hi/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

अतुल्यकालिक कार्य।

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | कार्य त्रुटि प्राप्त करता है जो कार्य पूरा होने के बाद उपलब्ध होता है। |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि यह कार्य वर्तमान में चल रहा है या नहीं। |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह कार्य रद्द कर दिया गया था। |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह कार्य त्रुटिपूर्ण था. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | अतुल्यकालिक कार्य की प्रगति प्राप्त करता है। |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | इस कार्य का परिणाम प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | इस कार्य को निरस्त करता है। आंतरिक अप्रबंधित संसाधनों को मुक्त न करने के जोखिम के साथ कार्य तुरंत पूरा हो जाता है। |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | इस कार्य को रद्द करता है। एल्गोरिथ्म के नियंत्रित रोक से कार्य सुरक्षित रूप से पूरा हो जाता है। |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | इस कार्य को चलाता है। |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | इस कार्य को चलाता है। |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | पूर्ण कॉलबैक प्रतिनिधि सेट करता है। |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | प्रगति कॉलबैक प्रतिनिधि सेट करता है। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* सभा [Aspose.PSD](../../)


