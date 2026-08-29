---
title: "MlstResource.Items"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية MlstResource. يحصل على أو يضبط الهياكل"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

يحصل أو يضبط البُنى.

```csharp
public OSTypeStructure[] Items { get; }
```

## أمثلة

الكود التالي يوضح دعم مورد MlstResource الذي يوفر آلية منخفضة المستوى للتعامل مع حالات الطبقة.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // تعطيل الطبقة 1 في الإطار 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### انظر أيضًا

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


