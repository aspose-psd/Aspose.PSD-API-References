---
title: "UnitArrayStructure.UnitArrayStructure"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "UnitArrayStructure कंस्ट्रक्टर। UnitArrayStructure क्लास का नया इंस्टेंस इनिशियलाइज़ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
{{< psd/tize >}}
## UnitArrayStructure constructor

[`UnitArrayStructure`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| keyName | ClassID | कुंजी का नाम। |
| unitType | UnitTypes | यूनिट का प्रकार। |
| values | Double[] | वैल्यूज़। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | वैल्यूज़ null नहीं होनी चाहिए |

## उदाहरण

निम्नलिखित कोड ObAr और UnFl हस्ताक्षरों के समर्थन को दर्शाता है।

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

### देखें भी

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


