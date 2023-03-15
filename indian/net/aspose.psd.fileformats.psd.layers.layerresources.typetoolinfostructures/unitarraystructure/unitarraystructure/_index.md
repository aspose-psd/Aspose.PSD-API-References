---
title: UnitArrayStructure.UnitArrayStructure
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: UnitArrayStructure नर्मत. क एक नय उदहरण प्ररंभ करत हैUnitArrayStructure वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
## UnitArrayStructure constructor

का एक नया उदाहरण प्रारंभ करता है[`UnitArrayStructure`](../) वर्ग.

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keyName | ClassID | कुंजी का नाम। |
| unitType | UnitTypes | इकाई का प्रकार। |
| values | Double[] | मूल्य। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | मान शून्य नहीं होने चाहिए |

### उदाहरण

निम्न कोड ObAr और UnFl हस्ताक्षरों के समर्थन को प्रदर्शित करता है।

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

### यह सभी देखें

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../unitarraystructure/)
* सभा [Aspose.PSD](../../../)


