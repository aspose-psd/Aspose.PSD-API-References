---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PattResourceData. تعيين مخزن بكسل النمط وحجم الهدف، وتحديث Width / Height، وتخزين البيانات للحفظ باستخدام وضع الضغط الافتراضي 0"
type: docs
weight: 110
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

يقوم بتعيين مخزن بكسل النمط وحجم الهدف، ويحدّث [`Width`](../width/) / [`Height`](../height/)، ويخزن البيانات للحفظ باستخدام وضع الضغط الافتراضي (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | Int32[] | بكسلات 32‑بت بتنسيق `0xAARRGGBB`. |
| الحدود | Rectangle | حدود البكسل للنمط. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | يجب أن يكون طول مصفوفة البكسلات مساويًا لمساحة الحدود. |

### انظر أيضًا

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


