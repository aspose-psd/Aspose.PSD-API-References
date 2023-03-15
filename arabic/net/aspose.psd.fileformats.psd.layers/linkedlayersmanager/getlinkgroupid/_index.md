---
title: LinkedLayersManager.GetLinkGroupId
second_title: Aspose.PSD لمرجع .NET API
description: LinkedLayersManager طريقة. يحصل على معرف مجموعة الارتباط المرتبط بالطبقة.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
## LinkedLayersManager.GetLinkGroupId method

يحصل على معرف مجموعة الارتباط المرتبط بالطبقة.

```csharp
public short GetLinkGroupId(Layer layer)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| layer | Layer | طبقة. |

### قيمة الإرجاع

معرف مجموعة الارتباط.

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* المجسم [Aspose.PSD](../../../)


