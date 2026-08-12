---
title: "Clase UnitArrayStructure"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.UnitArrayStructure clase. Define la clase UnitArrayStructure que contiene una matriz de valores Double y su unidad de medida. Se utiliza en los recursos de archivos PSD normalmente por ObjectArrayStructure"
type: docs
weight: 3660
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
{{< psd/tize >}}
## UnitArrayStructure class

Define la clase UnitArrayStructure que contiene una matriz de valores Double y su unidad de medida. Se utiliza en los recursos de archivos PSD, normalmente por [`ObjectArrayStructure`](../objectarraystructure/).

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [UnitArrayStructure](unitarraystructure/)(ClassID, UnitTypes, double[]) | Inicializa una nueva instancia de la clase `UnitArrayStructure`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key/) { get; } | Obtiene la clave de esta estructura de matriz de unidades. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Obtiene o establece el nombre de la clave. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length/) { get; } | Obtiene la longitud en bytes de [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype/) { get; set; } | Obtiene o establece el tipo de unidad de medida de los valores de `UnitArrayStructure`. |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount/) { get; } | Obtiene la cantidad de valores. |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/) { get; set; } | Obtiene o establece los valores de la estructura de matriz de unidades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Obtiene la longitud del encabezado. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Guarda la estructura en el contenedor de flujo especificado. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Guarda la estructura en el contenedor de flujo especificado. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey/) | Define la clave 'UnFl' `UnitArrayStructure`. |

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


