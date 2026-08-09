---
title: "LinkedLayersManager.GetLinkGroupId"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LinkedLayersManager. يحصل على معرف مجموعة الارتباط المرتبط بالطبقة"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLinkGroupId method

يحصل على معرف مجموعة الارتباط المرتبط بالطبقة.

```csharp
public short GetLinkGroupId(Layer layer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| طبقة | طبقة | الطبقة. |

### قيمة الإرجاع

معرف مجموعة الارتباط.

## أمثلة

المثال التالي يوضح كيف يمكنك تعديل الطبقات المرتبطة في Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // ربط جميع الطبقات في مجموعة مرتبطة واحدة
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // يحصل على المعرف لطبقة واحدة
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // يحصل على جميع الطبقات المرتبطة حسب معرف مجموعة الارتباط.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // فك ربط كل طبقة من المجموعة
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // يسترجع NULL لمعرف مجموعة الارتباط التي لا تحتوي على طبقات في المجموعة.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### انظر أيضًا

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


