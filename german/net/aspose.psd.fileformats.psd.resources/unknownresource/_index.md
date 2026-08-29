---
title: "Klasse UnknownResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Resources.UnknownResource Klasse. Die unbekannte Ressource. Wenn ein Ressourcenblock nicht erkannt wird, wird dieser Ressourcenblock erstellt"
type: docs
weight: 4410
url: /de/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
{{< psd/tize >}}
## UnknownResource class

Die unbekannte Ressource. Wenn ein Ressourcenblock nicht erkannt wird, wird dieser Ressourcenblock erstellt.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Gibt die Ressourcendaten zurück. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Ruft die Größe der Ressourcendaten in Bytes ab. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung der Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Liest die minimal erforderliche PSD-Version. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-Zeichenkette, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock in den angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

### Siehe auch

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


