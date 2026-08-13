---
title: "فئة QuickMaskInformationResource"
type: docs
weight: 220
url: /ar/python-net/aspose.psd.fileformats.psd.resources/quickmaskinformationresource/
---

**Summary:** Quick mask information resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.QuickMaskInformationResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [QuickMaskInformationResource()](#QuickMaskInformationResource__1) | ينشئ مثلاً جديداً من فئة QuickMaskInformationResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| channel_id | short | r/w | يحصل أو يضبط معرف القناة. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| id | short | r/w | يحصل أو يعيّن المعرف الفريد للمورد. |
| is_mask_empty | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه المثيلة قناعًا فارغًا. |
| minimal_version | int | r | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| name | string | r/w | يحصل أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0). |
| signature | int | r | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| الحجم | int | r | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ كتلة المورد إلى الدفق المحدد. |
| validate_values() | يتحقق من صحة قيم المورد. |


### Constructor: QuickMaskInformationResource() {#QuickMaskInformationResource__1}


```
 QuickMaskInformationResource() 
```

ينشئ مثلاً جديداً من فئة QuickMaskInformationResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

