---
title: UnitArrayStructure.UnitArrayStructure
second_title: Aspose.PSD för .NET API-referens
description: UnitArrayStructure byggare. Initierar en ny instans avUnitArrayStructure class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
## UnitArrayStructure constructor

Initierar en ny instans av[`UnitArrayStructure`](../) class.

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyName | ClassID | Nyckelns namn. |
| unitType | UnitTypes | Typ av enhet. |
| values | Double[] | Värdena. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | värden får inte vara null |

### Exempel

Följande kod visar stödet för ObAr- och UnFl-signaturerna.

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

### Se även

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../unitarraystructure/)
* hopsättning [Aspose.PSD](../../../)


