---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "CmykColorHelper-Methode. Konvertiert RGB zu CMYK unter Verwendung benutzerdefinierter ICC‑Profile"
type: docs
weight: 120
url: /de/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | Int32[] | Die RGB‑Farben werden als 32‑Bit‑Ganzzahlwerte dargestellt. |
| startIndex | Int32 | Der Startindex der RGB‑Farbe. |
| length | Int32 | Die Anzahl der zu konvertierenden RGB‑Pixel. |
| rgbIccStream | Stream | Der RGB‑Profil‑Stream. |
| cmykIccStream | Stream | Der CMYK‑Profil‑Stream. |

### Rückgabewert

Die CMYK‑Farben werden als Byte‑Array dargestellt.

### Siehe auch

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


