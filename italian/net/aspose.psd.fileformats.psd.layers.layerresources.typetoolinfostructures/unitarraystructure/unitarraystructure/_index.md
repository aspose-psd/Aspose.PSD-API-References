---
title: UnitArrayStructure.UnitArrayStructure
second_title: Aspose.PSD per riferimento API .NET
description: UnitArrayStructure costruttore. Inizializza una nuova istanza diUnitArrayStructure classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
## UnitArrayStructure constructor

Inizializza una nuova istanza di[`UnitArrayStructure`](../) classe.

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keyName | ClassID | Nome della chiave. |
| unitType | UnitTypes | Tipo di unità. |
| values | Double[] | I valori. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | i valori non devono essere nulli |

### Esempi

Il codice seguente dimostra il supporto delle firme ObAr e UnFl.

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

### Guarda anche

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../unitarraystructure/)
* assemblea [Aspose.PSD](../../../)


