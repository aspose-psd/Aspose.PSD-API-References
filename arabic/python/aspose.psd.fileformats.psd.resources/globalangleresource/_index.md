---
title: "فئة GlobalAngleResource"
type: docs
weight: 100
url: /ar/python-net/aspose.psd.fileformats.psd.resources/globalangleresource/
---

**Summary:** Global angle resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GlobalAngleResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GlobalAngleResource()](#GlobalAngleResource__1) | يُنشئ مثيلاً جديدًا من الفئة GlobalAngleResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| global_angle | int | r/w | يحصل أو يضبط الزاوية العامة. |
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


### Constructor: GlobalAngleResource() {#GlobalAngleResource__1}


```
 GlobalAngleResource() 
```

يُنشئ مثيلاً جديدًا من الفئة GlobalAngleResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

