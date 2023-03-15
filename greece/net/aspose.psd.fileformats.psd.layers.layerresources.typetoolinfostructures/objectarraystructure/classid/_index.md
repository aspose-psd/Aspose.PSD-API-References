---
title: ObjectArrayStructure.ClassID
second_title: Aspose.PSD για Αναφορά API .NET
description: ObjectArrayStructure ιδιοκτησία. Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πίνακα αντικειμένων.
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/
---
## ObjectArrayStructure.ClassID property

Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πίνακα αντικειμένων.

```csharp
public ClassID ClassID { get; set; }
```

### Αξία περιουσίας

Η κλάση του πίνακα αντικειμένων ID.

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των υπογραφών ObAr και UnFl.

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

### Δείτε επίσης

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [ObjectArrayStructure](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure/)
* συνέλευση [Aspose.PSD](../../../)


