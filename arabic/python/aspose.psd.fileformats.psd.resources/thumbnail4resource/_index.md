---
title: "فئة Thumbnail4Resource"
type: docs
weight: 240
url: /ar/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | يقوم بإنشاء نسخة جديدة من فئة Thumbnail4Resource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | توقيع مورد Photoshop العادي. |
| bits_pixel | short | r/w | يحصل أو يضبط عدد البتات في البكسل. |
| data_size | int | r | يحصل على حجم بيانات المورد بالبايت. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | يحصل أو يضبط تنسيق بيانات الصورة المصغرة. |
| الارتفاع | int | r/w | يحصل أو يضبط ارتفاع الصورة المصغرة بالبكسل. |
| id | short | r/w | يحصل أو يعيّن المعرف الفريد للمورد. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | يحصل أو يضبط خيارات JPEG. مناسب عندما يتم حفظ مورد الصورة المصغرة بتنسيق ملف JPEG فقط. هذا الخيار لا يؤثر عندما يكون تنسيق RAW محددًا. |
| minimal_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب. |
| name | string | r/w | يحصل أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0). |
| planes_count | short | r/w | يحصل على أو يضبط عدد المستويات. |
| signature | int | r | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| الحجم | int | r | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| size_after_compression | int | r | يحصل على أو يضبط الحجم بعد الضغط. يُستخدم للتحقق من التناسق. |
| thumbnail_argb_32_data | int | r/w | يحصل على أو يضبط بيانات الصورة المصغرة ARGB 32-بت. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | يحصل على أو يضبط بيانات الصورة المصغرة. |
| total_size | int | r | يحصل على إجمالي حجم البيانات. |
| width | int | r/w | يحصل على أو يضبط عرض الصورة المصغرة بالبكسل. |
| width_bytes | int | r | يحصل على عرض الصف بالبايت. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream)](#save_stream_1) | يحفظ بيانات كتلة المورد. |
| validate_values() | يتحقق من صحة قيم المورد. |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

يقوم بإنشاء نسخة جديدة من فئة Thumbnail4Resource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

يحفظ بيانات كتلة المورد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

