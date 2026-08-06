---
title: "IImageExporter"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مُصدّر الصورة."
type: docs
weight: 121
url: /ar/java/com.aspose.psd/iimageexporter/
---
```
public interface IImageExporter
```

مصدّر الصور. يمكنه تصدير البيانات من تنسيق Aspose.Imaging الداخلي إلى تنسيق بيانات محدد.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | يصدّر بيانات الصورة المحددة إلى تنسيق البيانات المحدد. |
| [export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | يصدّر بيانات الصورة المحددة إلى تنسيق البيانات المحدد. |
### export(Image image, OutputStream stream, ImageOptionsBase optionsBase) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase)
```


يصدّر بيانات الصورة المحددة إلى تنسيق البيانات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | بيانات الصورة المراد تصديرها. |
| stream | java.io.OutputStream | الدفق لتصدير البيانات إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات تصدير الصورة |

### export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#export-com.aspose.psd.Image-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public abstract void export(Image image, OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يصدّر بيانات الصورة المحددة إلى تنسيق البيانات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | بيانات الصورة المراد تصديرها. |
| stream | java.io.OutputStream | الدفق لتصدير البيانات إليه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | خيارات تصدير الصورة |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | مستطيل الحدود. |

