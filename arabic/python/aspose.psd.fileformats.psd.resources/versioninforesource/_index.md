---
title: "فئة VersionInfoResource"
type: docs
weight: 300
url: /ar/python-net/aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Summary:** Version Info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.VersionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [VersionInfoResource()](#VersionInfoResource__1) | ينشئ مثيلاً جديداً من فئة VersionInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| file_version | uint | r/w | يحصل أو يضبط إصدار الملف. |
| has_real_merged_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه المثيلة تحتوي على بيانات مدمجة حقيقية. |
| id | short | r/w | يحصل أو يعيّن المعرف الفريد للمورد. |
| minimal_version | int | r | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| name | string | r/w | يحصل أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0). |
| reader_name | string | r/w | يحصل أو يضبط اسم القارئ. |
| signature | int | r | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| الحجم | int | r | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| version | uint | r/w | يحصل أو يعيّن الإصدار. |
| writer_name | string | r/w | يحصل أو يضبط اسم الكاتب. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ كتلة المورد إلى الدفق المحدد. |
| validate_values() | يتحقق من صحة قيم المورد. |


### Constructor: VersionInfoResource() {#VersionInfoResource__1}


```
 VersionInfoResource() 
```

ينشئ مثيلاً جديداً من فئة VersionInfoResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

