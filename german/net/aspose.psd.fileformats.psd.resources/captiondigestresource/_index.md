---
title: Class CaptionDigestResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Resources.CaptionDigestResource klas. CaptionDigestRessource
type: docs
weight: 3660
url: /de/net/aspose.psd.fileformats.psd.resources/captiondigestresource/
---
## CaptionDigestResource class

CaptionDigest-Ressource

```csharp
public sealed class CaptionDigestResource : ResourceBlock
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CaptionDigestResource](captiondigestresource/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/captiondigestresource/datasize/) { get; } | Ruft die Ressourcendatengröße in Byte ab. |
| [Digest](../../aspose.psd.fileformats.psd.resources/captiondigestresource/digest/) { get; set; } | Ruft den Digest ab oder legt ihn fest. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung für die Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/captiondigestresource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
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


