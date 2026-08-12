---
title: "Klasse NameStructure"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure klasse. De Name-structuursleutel 0x6E616D65, die 'name' in ASCII spelt, is een eenvoudige structuur die wordt gebruikt om een Unicode- of Pascal-stijl tekenreeks op te slaan die de naam van een element vertegenwoordigt, zoals een laagpad of aanpassing."
type: docs
weight: 3580
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/
---
{{< psd/tize >}}
## NameStructure class

De Name-structuur (sleutel: 0x6E616D65, die "name" in ASCII spelt) is een eenvoudige structuur die wordt gebruikt om een Unicode- of Pascal-stijl tekenreeks op te slaan die de naam van een element vertegenwoordigt, zoals een laag, pad of aanpassing.

```csharp
public sealed class NameStructure : OSTypeStructure
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [NameStructure](namestructure/)(ClassID) | Initialiseert een nieuw exemplaar van de `NameStructure`-klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/key/) { get; } | Haalt de sleutel op. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Haalt of stelt de sleutelnaam in. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/length/) { get; } | Haalt de lengte in bytes op van [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/value/) { get; set; } | Haalt of stelt de waarde van een Name-structuur in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Haalt de headerlengte op. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Slaat de structuur op in de opgegeven streamcontainer. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Slaat de structuur op in de opgegeven streamcontainer. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/structurekey/) | De Name-structuursleutel. |

## Voorbeelden

De volgende code demonstreert de ondersteuning van NameStructure.

```csharp
[C#]

string inputFile = "Mixer_ipad_Hand_W_crash.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(inputFile, new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    //// Bestand is succesvol geladen

    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);

    // Sla het testbestand op zonder wijzigingen
    psdImage.Save(outputFile);

    //// Bestand moet in PS worden geopend zonder fouten
}

// Controleer of de structuren van belichtingseffecten correct zijn opgeslagen
using (var psdImage = (PsdImage)Image.Load(
           outputFile,
           new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### Zie ook

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


