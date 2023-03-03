---
title: Class LinkedLayersManager
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager فصل. فئة مدير الطبقات المرتبطة .
type: docs
weight: 3400
url: /ar/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

فئة مدير الطبقات المرتبطة .

```csharp
public sealed class LinkedLayersManager
```

## طُرق

| اسم | وصف |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | يحصل على الطبقات عن طريق معرف مجموعة الارتباط. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | يحصل على معرف مجموعة الارتباط المرتبط بالطبقة. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | يربط طبقات الإدخال ويعيد LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | فك ارتباط الطبقة .. |

### أمثلة

يوضح المثال التالي كيف يمكنك التعامل مع الطبقات المرتبطة في Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // ربط كل الطبقات في مجموعة مرتبطة واحدة
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // يحصل على معرف لطبقة واحدة
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // يحصل على جميع الطبقات المرتبطة عن طريق معرف مجموعة الارتباط.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // إلغاء ربط كل طبقة بالمجموعة
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // يسترد NULL لمعرّف مجموعة الارتباط الذي لا يحتوي على طبقات في المجموعة.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* المجسم [Aspose.PSD](../../)


