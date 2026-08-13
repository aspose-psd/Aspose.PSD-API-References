---
title: "فئة GridAndGuidesResouce"
type: docs
weight: 110
url: /ar/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | ينشئ مثيلاً جديداً من فئة GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| grid_cycle_x | int | r/w | يحصل على أو يضبط دورة الشبكة الأفقية. القيمة الافتراضية هي 576. |
| grid_cycle_y | int | r/w | يحصل على أو يضبط دورة الشبكة العمودية. القيمة الافتراضية هي 576. |
| guide_count | int | r | يحصل على عدد كتل موارد الدليل. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | يحصل على أو يضبط الأدلة. |
| header_version | int | r/w | يحصل أو يعيّن نسخة الرأس. يجب أن تكون هذه القيمة دائمًا 1. |
| id | short | r/w | يحصل أو يعيّن المعرف الفريد للمورد. |
| minimal_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب. |
| name | string | r/w | يحصل أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0). |
| signature | int | r | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| الحجم | int | r | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ كتلة المورد إلى الدفق المحدد. |
| validate_values() | يتحقق من صحة قيم المورد. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

ينشئ مثيلاً جديداً من فئة GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

