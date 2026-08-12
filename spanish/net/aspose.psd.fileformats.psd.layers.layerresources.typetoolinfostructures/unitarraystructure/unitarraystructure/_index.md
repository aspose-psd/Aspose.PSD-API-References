---
title: "UnitArrayStructure.UnitArrayStructure"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor de UnitArrayStructure. Inicializa una nueva instancia de la clase UnitArrayStructure"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unitarraystructure/
---
{{< psd/tize >}}
## UnitArrayStructure constructor

Inicializa una nueva instancia de la clase [`UnitArrayStructure`](../).

```csharp
public UnitArrayStructure(ClassID keyName, UnitTypes unitType, double[] values)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| keyName | ClassID | Nombre de la clave. |
| unitType | UnitTypes | Tipo de la unidad. |
| values | Double[] | Los valores. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Los valores no deben ser nulos. |

## Ejemplos

El siguiente código demuestra el soporte de las firmas ObAr y UnFl.

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

### Ver también

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* enum [UnitTypes](../../unittypes/)
* class [UnitArrayStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


