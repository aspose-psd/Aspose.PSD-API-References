---
title: "فئة ColorHalftoneInformationResource"
type: docs
weight: 50
url: /ar/python-net/aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/
---

**Summary:** Halftoning resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ColorHalftoneInformationResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ColorHalftoneInformationResource()](#ColorHalftoneInformationResource__1) | ينشئ مثيلًا جديدًا من الفئة ColorHalftoneInformationResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| halftone_data | byte | r/w | يحصل أو يعيّن بيانات نصف النغمة. |
| id | short | r/w | يحصل أو يعيّن المعرف الفريد للمورد. |
| minimal_version | int | r | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| name | string | r/w | يحصل أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0). |
| signature | int | r | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| الحجم | int | r | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ كتلة المورد إلى الدفق المحدد. |
| validate_values() | يتحقق من صحة قيم المورد. |


### Constructor: ColorHalftoneInformationResource() {#ColorHalftoneInformationResource__1}


```
 ColorHalftoneInformationResource() 
```

ينشئ مثيلًا جديدًا من الفئة ColorHalftoneInformationResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

