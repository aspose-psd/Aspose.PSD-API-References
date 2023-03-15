---
title: ObjectArrayStructure.ObjectArrayStructure
second_title: Aspose.PSD για Αναφορά API .NET
description: ObjectArrayStructure κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουObjectArrayStructure τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/objectarraystructure/
---
## ObjectArrayStructure(string, string, OSTypeStructure[]) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`ObjectArrayStructure`](../) τάξη.

```csharp
public ObjectArrayStructure(string keyName, string classIdName, OSTypeStructure[] structures)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keyName | String | Όνομα του κλειδιού. |
| classIdName | String | Όνομα του αναγνωριστικού κλάσης. |
| structures | OSTypeStructure[] | Οι δομές. |

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

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [ObjectArrayStructure](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure/)
* συνέλευση [Aspose.PSD](../../../)

---

## ObjectArrayStructure(int, ClassID, ClassID, string, OSTypeStructure[]) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`ObjectArrayStructure`](../) τάξη.

```csharp
public ObjectArrayStructure(int key, ClassID keyName, ClassID classID, string className, 
    OSTypeStructure[] structures)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | Int32 | Το ακέραιο κλειδί. |
| keyName | ClassID | Το όνομα κλειδιού. |
| classID | ClassID | Το αναγνωριστικό κλάσης. |
| className | String | Όνομα της τάξης. |
| structures | OSTypeStructure[] | Οι δομές. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | classID είναι μηδενικό |

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
* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* class [ObjectArrayStructure](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure/)
* συνέλευση [Aspose.PSD](../../../)


