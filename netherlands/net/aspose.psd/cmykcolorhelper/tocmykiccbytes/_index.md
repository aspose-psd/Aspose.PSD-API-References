---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD voor .NET API-referentie
description: CmykColorHelper methode. Converteert RGB naar CMYK met behulp van aangepaste ICCprofielen.
type: docs
weight: 120
url: /nl/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Converteert RGB naar CMYK met behulp van aangepaste ICC-profielen.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | Int32[] | De RGB-kleuren worden weergegeven als 32-bits gehele getallen. |
| startIndex | Int32 | De startindex van RGB-kleur. |
| length | Int32 | Het aantal RGB-pixels dat moet worden geconverteerd. |
| rgbIccStream | Stream | De RGB-profielstream. |
| cmykIccStream | Stream | De CMYK-profielstroom. |

### Winstwaarde

De CMYK-kleuren gepresenteerd als een byte-array.

### Zie ook

* class [CmykColorHelper](../)
* naamruimte [Aspose.PSD](../../cmykcolorhelper/)
* montage [Aspose.PSD](../../../)


