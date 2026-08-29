---
title: "ObjectArrayStructure.ClassID"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ObjectArrayStructure. تحصل أو تعين معرف فئة مصفوفة الكائن"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/
---
{{< psd/tize >}}
## ObjectArrayStructure.ClassID property

يحصل أو يعيّن معرف فئة مصفوفة الكائن.

```csharp
public ClassID ClassID { get; set; }
```

### Property Value

معرف فئة مصفوفة الكائن.

## أمثلة

الكود التالي يوضح دعم توقيعات ObAr و UnFl.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### انظر أيضًا

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [ObjectArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


