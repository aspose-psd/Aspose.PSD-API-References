---
title: "Klasse ResolutionInfoResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource Klasse. Ressource für Auflösungsinformationen."
type: docs
weight: 4350
url: /de/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
{{< psd/tize >}}
## ResolutionInfoResource class

Die Auflösungsinfo-Ressource

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Ruft die Größe der Ressourcendaten in Bytes ab. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | Horizontale DPI. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Liest oder setzt die Höheneinheit der Anzeige. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Anzeigeeinheiten für die horizontale Auflösung. Dies wirkt sich nur auf die Benutzeroberfläche aus; die Auflösung wird weiterhin in der PSD-Datei als Pixel/Zoll gespeichert. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung der Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-Zeichenkette, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten ab. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | Vertikale DPI. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Anzeigeeinheiten für die vertikale Auflösung. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Liest oder setzt die Anzeigeeinheit für die Breite. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock in den angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

### Siehe auch

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


