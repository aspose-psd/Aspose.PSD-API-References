---
title: Class UnknownResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Resources.UnknownResource klas. Die unbekannte Ressource. Wenn ein Ressourcenblock nicht erkannt wird wird dieser Ressourcenblock erstellt.
type: docs
weight: 3940
url: /de/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
## UnknownResource class

Die unbekannte Ressource. Wenn ein Ressourcenblock nicht erkannt wird, wird dieser Ressourcenblock erstellt.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Ruft die Ressourcendaten ab. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Ruft die Ressourcendatengröße in Byte ab. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung für die Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-String, aufgefüllt, um die Größe gleichmäßig zu machen (ein Nullname besteht aus zwei Bytes von 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Ressourcenblockgröße in Byte ab, einschließlich seiner Daten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock im angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

### Siehe auch

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Montage [Aspose.PSD](../../)


