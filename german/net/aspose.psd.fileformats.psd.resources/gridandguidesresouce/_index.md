---
title: "Klasse GridAndGuidesResouce"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce Klasse. Stellt die Raster‑ und Führungslinien‑Ressource dar"
type: docs
weight: 4200
url: /de/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
{{< psd/tize >}}
## GridAndGuidesResouce class

Stellt die Raster- und Führungs-Ressource dar.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Ruft die Größe der Ressourcendaten in Bytes ab. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Liest oder setzt den horizontalen Rasterzyklus. Der Standardwert ist 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Liest oder setzt den vertikalen Rasterzyklus. Der Standardwert ist 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Ermittelt die Anzahl der Leitfaden-Ressourcenblöcke. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Liest oder legt die Leitfäden fest. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Liest oder legt die Header-Version fest. Dieser Wert sollte immer 1 sein. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung der Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Liest die minimal erforderliche PSD-Version. |
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


