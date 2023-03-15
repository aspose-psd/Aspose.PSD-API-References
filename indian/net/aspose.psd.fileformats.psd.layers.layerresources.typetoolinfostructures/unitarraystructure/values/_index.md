---
title: UnitArrayStructure.Values
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: UnitArrayStructure संपत्त. इकई सरण संरचन मन प्रप्त य सेट करत है
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/
---
## UnitArrayStructure.Values property

इकाई सरणी संरचना मान प्राप्त या सेट करता है।

```csharp
public double[] Values { get; set; }
```

### संपत्ति मूल्य

इकाई सरणी संरचना मान.

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | Values संपत्ति शून्य नहीं होनी चाहिए। |

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

* class [UnitArrayStructure](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../unitarraystructure/)
* सभा [Aspose.PSD](../../../)


