---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "IfxsResource حقل. مفتاح معلومات أداة النوع"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

مفتاح معلومات أداة النوع.

```csharp
public const int TypeToolKey;
```

## أمثلة

الكود التالي يوضح دعم IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // المثال يحتوي على طبقتين مجموعتين مع تأثيرات
    // طبقة مجموعة بتأثير واحد
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // طبقة مجموعة بعدة تأثيرات
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // احصل على عدد التأثيرات وتحقق من كميتها
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // تأثير واحد في طبقة المجموعة موجود في المورد 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // اثنان أو أكثر من التأثيرات في طبقة المجموعة موجودة في المورد 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // أضف ظلًا ثالثًا إلى طبقة المجموعة التي تحتوي على تأثيرات متعددة
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### انظر أيضًا

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


