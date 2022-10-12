---
title: UnitArrayStructure
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Definisce la classe UnitArrayStructure che contieneDouble array di valori e la loro unità di misura. Viene utilizzato nelle risorse del file PSD solitamente daObjectArrayStructure./objectarraystructure .
type: docs
weight: 3210
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
## UnitArrayStructure class

Definisce la classe UnitArrayStructure che contieneDouble array di valori e la loro unità di misura. Viene utilizzato nelle risorse del file PSD, solitamente da[`ObjectArrayStructure`](../objectarraystructure) .

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [UnitArrayStructure](unitarraystructure)(ClassID, UnitTypes, double[]) | Inizializza una nuova istanza di[`UnitArrayStructure`](../unitarraystructure) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key) { get; } | Ottiene questa chiave della struttura dell'array di unità. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname) { get; set; } | Ottiene o imposta il nome della chiave. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length) { get; } | Ottiene il[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) lunghezza in byte. |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype) { get; set; } | Ottiene o imposta il tipo di unità di misura di[`UnitArrayStructure`](../unitarraystructure) valori. |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount) { get; } | Ottiene il conteggio del valore. |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values) { get; set; } | Ottiene o imposta i valori della struttura della matrice dell'unità. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength)() | Ottiene la lunghezza dell'intestazione. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save)(StreamContainer) | Salva la struttura nel contenitore del flusso specificato. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname)(StreamContainer) | Salva la struttura nel contenitore del flusso specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey) | Definisce 'UnFl'[`UnitArrayStructure`](../unitarraystructure) chiave. |

### Esempi

Il codice seguente mostra il supporto delle firme ObAr e UnFl.

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
