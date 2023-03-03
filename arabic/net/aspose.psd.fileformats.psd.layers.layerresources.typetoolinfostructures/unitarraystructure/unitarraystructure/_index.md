---
title: UnitArrayStructure.UnitArrayStructure
second_title: Aspose.PSD لمرجع .NET API
description: UnitArrayStructure البناء. يقوم بتهيئة مثيل جديد لملفUnitArrayStructure فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
## UnitArrayStructure constructor

يقوم بتهيئة مثيل جديد لملف[`UnitArrayStructure`](../) فئة .

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| keyName | ClassID | اسم المفتاح. |
| unitType | UnitTypes | نوع الوحدة. |
| values | Double[] | القيم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | يجب ألا تكون القيم خالية |

### أمثلة

يوضح الكود التالي دعم تواقيع ObAr و UnFl.

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

### أنظر أيضا

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../unitarraystructure/)
* المجسم [Aspose.PSD](../../../)


