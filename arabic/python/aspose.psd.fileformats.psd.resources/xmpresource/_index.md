---
title: "فئة XmpResource"
type: docs
weight: 330
url: /ar/python-net/aspose.psd.fileformats.psd.resources/xmpresource/
---

**Summary:** Represents the XMP metadata resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.XmpResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpResource()](#XmpResource__1) | ينشئ مثيلًا جديدًا من فئة XmpResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| id | short | r/w | يحصل أو يعيّن المعرف الفريد للمورد. |
| minimal_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب. |
| name | string | r/w | يحصل أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0). |
| signature | int | r | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| الحجم | int | r | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | احصل أو عيّن حاوية بيانات XMP |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ كتلة المورد إلى الدفق المحدد. |
| validate_values() | يتحقق من صحة قيم المورد. |


### Constructor: XmpResource() {#XmpResource__1}


```
 XmpResource() 
```

ينشئ مثيلًا جديدًا من فئة XmpResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

