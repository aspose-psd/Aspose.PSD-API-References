---
title: "Klasse ObjectArrayStructure"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.ObjectArrayStructure Klasse. Definiert die ObjectArrayStructure Klasse, die normalerweise ein UnitArrayStructure-Array enthält. Sie wird in den PSD-Dateiresourcen wie PlLd Resource und SoLd Resource verwendet."
type: docs
weight: 3590
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
{{< psd/tize >}}
## ObjectArrayStructure class

Definiert die Klasse ObjectArrayStructure, die normalerweise ein [`UnitArrayStructure`](../unitarraystructure/)-Array enthält. Sie wird in den PSD-Dateiresourcen verwendet, wie z. B. PlLd Resource und SoLd Resource.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure/#constructor_1)(string, string, OSTypeStructure[]) | Initialisiert eine neue Instanz der `ObjectArrayStructure`-Klasse. |
| [ObjectArrayStructure](objectarraystructure/#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | Initialisiert eine neue Instanz der `ObjectArrayStructure`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/) { get; set; } | Liest oder setzt die Klassen-ID des Objektarray. |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname/) { get; set; } | Liest oder setzt den Klassennamen des Objektarray. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key/) { get; } | Liest den Strukturenschlüssel des Objektarray. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Liest oder setzt den Schlüsselnamen. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length/) { get; } | Liest die Länge des [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes. |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount/) { get; } | Liest die Anzahl der Untersubstrukturen des Objektarray. |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures/) { get; set; } | Liest oder setzt eine Kopie eines Arrays von Strukturen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Liest die Header-Länge. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Speichert die Struktur im angegebenen Stream-Container. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Speichert die Struktur im angegebenen Stream-Container. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey/) | Identifiziert den 'ObAr'-Strukturenschlüssel. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der ObAr- und UnFl-Signaturen.

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

### Siehe auch

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


