---
title: "Klasse ResourceBlock"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.ResourceBlock class. Der Ressourcenblock"
type: docs
weight: 4070
url: /de/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
## ResourceBlock class

Der Ressourcenblock.

```csharp
public abstract class ResourceBlock
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Ruft die Größe der Ressourcendaten in Bytes ab. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung der Ressource ab oder legt sie fest. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-Zeichenkette, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock in den angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | Die Ressourcensignatur von ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | Die reguläre Photoshop‑Ressourcensignatur. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | Stellt den Zustand des Ressourcenblocks dar. |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


