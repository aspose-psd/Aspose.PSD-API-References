---
title: LinkedLayersManager.GetLayersByLinkGroupId
second_title: Aspose.PSD لمرجع .NET API
description: LinkedLayersManager طريقة. يحصل على الطبقات عن طريق معرف مجموعة الارتباط.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
## LinkedLayersManager.GetLayersByLinkGroupId method

يحصل على الطبقات عن طريق معرف مجموعة الارتباط.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| linkGroupId | Int16 | معرف مجموعة الارتباط. |

### قيمة الإرجاع

صفيف الطبقات.

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


