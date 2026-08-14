---
title: "IAsyncTask क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| is_busy | bool | r | इस कार्य के वर्तमान में चल रहे होने को दर्शाने वाला मान प्राप्त करता है। |
| is_canceled | bool | r | इस कार्य के रद्द किए जाने को दर्शाने वाला मान प्राप्त करता है। |
| is_faulted | bool | r | इस कार्य के त्रुटिपूर्ण होने को दर्शाने वाला मान प्राप्त करता है। |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | असिंक्रोनस कार्य की प्रगति प्राप्त करता है। |
| result | object | r | इस कार्य का परिणाम प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| abort() | इस कार्य को समाप्त करता है।<br/>            कार्य तुरंत पूरा हो जाता है, लेकिन आंतरिक अनमैनेज्ड संसाधनों को मुक्त न करने का जोखिम रहता है। |
| cancel() | इस कार्य को रद्द करता है।<br/>            कार्य एल्गोरिदम को नियंत्रित रूप से रोककर सुरक्षित रूप से पूरा होता है। |
| run_async() | इस कार्य को चलाता है। |


