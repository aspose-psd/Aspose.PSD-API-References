---
title: "Aufzählung LayerLockType"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType Enum. Optionen für die Ebenensperre"
type: docs
weight: 2890
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
{{< psd/tize >}}
## LayerLockType enumeration

Ebenen‑Sperroptionen

```csharp
[Flags]
public enum LayerLockType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | Keine Ebenensperre |
| LockTransparentPixels | `1` | Teilweise Sperre einer Ebene – Beschränkt die Bearbeitung auf die undurchsichtigen Bereiche der Ebene. Diese Option entspricht der Option "Transparenz erhalten" in früheren Versionen von Photoshop. |
| LockImagePixels | `2` | Teilweise Sperre einer Ebene – Verhindert die Änderung der Pixel der Ebene mit den Malwerkzeugen. |
| LockPosition | `4` | Teilweise Sperre einer Ebene – Verhindert, dass die Pixel der Ebene verschoben werden. |
| LockAll | `7` | Alle Eigenschaften einer Ebene sperren |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


