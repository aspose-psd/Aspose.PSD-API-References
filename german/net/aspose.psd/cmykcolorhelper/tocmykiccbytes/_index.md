---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD für .NET-API-Referenz
description: CmykColorHelper methode. Konvertiert RGB in CMYK mit benutzerdefinierten ICCProfilen.
type: docs
weight: 120
url: /de/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Konvertiert RGB in CMYK mit benutzerdefinierten ICC-Profilen.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | Int32[] | Die RGB-Farben werden als 32-Bit-Ganzzahlwerte dargestellt. |
| startIndex | Int32 | Der Startindex der RGB-Farbe. |
| length | Int32 | Die Anzahl der zu konvertierenden RGB-Pixel. |
| rgbIccStream | Stream | Der RGB-Profilstream. |
| cmykIccStream | Stream | Der CMYK-Profilstream. |

### Rückgabewert

Die CMYK-Farben, dargestellt als Byte-Array.

### Siehe auch

* class [CmykColorHelper](../)
* namensraum [Aspose.PSD](../../cmykcolorhelper/)
* Montage [Aspose.PSD](../../../)


