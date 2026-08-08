---
title: "IPsdColorPalette"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De pasd-kleurenpalet"
type: docs
weight: 134
url: /nl/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

De pasd-kleurenpalet
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Haalt de ruwe gegevens van de kleurpaletinvoer op. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Haalt het aantal ruwe kleurpaletinvoer op. |
| [getTransparentColor()](#getTransparentColor--) | Haalt de transparante kleur op. |
| [getTransparentIndex()](#getTransparentIndex--) | Haalt de index van de transparante kleur op. |
| [hasTransparentColor()](#hasTransparentColor--) | Haalt een waarde op die aangeeft of een transparante kleur bestaat. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Haalt de ruwe gegevens van de kleurpaletinvoer op.

Value: De ruwe gegevens van de kleurenpaletitems.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Haalt het aantal ruwe kleurpaletinvoer op.

Value: Het ruwe aantal kleurenpaletitems.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Haalt de transparante kleur op.

Value: De transparante kleur.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Haalt de index van de transparante kleur op.

Value: De index van de transparante kleur.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Haalt een waarde op die aangeeft of een transparante kleur bestaat.

Value:  true  als er een transparante kleur bestaat; anders,  false .

**Returns:**
boolean
