---
title: "Klasse PathStructure"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure Klasse. Die Pfadstruktur"
type: docs
weight: 3610
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

Die Pfadstruktur.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | Initialisiert eine neue Instanz der `PathStructure` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Liest den Struktur-Schlüssel. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Liest oder setzt den Schlüsselnamen. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | Liest die Länge des [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Liest oder setzt den Pfad. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Liest oder setzt das Pfadpräfix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Liest die Header-Länge. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Speichert die Struktur im angegebenen Stream-Container. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Speichert die Struktur im angegebenen Stream-Container. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Identifiziert den Struktur-Schlüssel. |

## Beispiele

Der folgende Code demonstriert die Fähigkeit, eine Datei mit der PathStructure-Struktur zu laden.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Siehe auch

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


