---
title: Enum TextRenderingHint
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.TextRenderingHint opsomming. Specificeert de kwaliteit van tekstweergave.
type: docs
weight: 5700
url: /nl/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

Specificeert de kwaliteit van tekstweergave.

```csharp
public enum TextRenderingHint
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| SystemDefault | `0` | Elk karakter wordt getekend met zijn glyph-bitmap, met de standaard weergavehint van het systeem. De tekst wordt getekend met de instellingen voor het gladmaken van lettertypen die de gebruiker voor het systeem heeft geselecteerd. |
| SingleBitPerPixelGridFit | `1` | Elk karakter wordt getekend met zijn glyph-bitmap. Hinting wordt gebruikt om het uiterlijk van tekens op stelen en kromming te verbeteren. |
| SingleBitPerPixel | `2` | Elk karakter wordt getekend met zijn glyph-bitmap. Hints worden niet gebruikt. |
| AntiAliasGridFit | `3` | Elk personage wordt getekend met behulp van zijn anti-aliased glyph-bitmap met hints. Veel betere kwaliteit dankzij antialiasing, maar tegen hogere prestatiekosten. |
| AntiAlias | `4` | Elk personage wordt zonder hints getekend met behulp van zijn anti-aliased glyph-bitmap. Betere kwaliteit dankzij antialiasing. Verschillen in stambreedte kunnen merkbaar zijn omdat hinting is uitgeschakeld. |
| ClearTypeGridFit | `5` | Elk karakter wordt getekend met zijn glyph ClearType-bitmap met hints. De hoogste kwaliteitsinstelling. Gebruikt om te profiteren van ClearType-lettertypefuncties. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


