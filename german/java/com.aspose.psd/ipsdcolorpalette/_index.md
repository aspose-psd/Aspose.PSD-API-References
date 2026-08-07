---
title: "IPsdColorPalette"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die pasd-Farbpalette"
type: docs
weight: 134
url: /de/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

Die pasd-Farbpalette
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Liefert die Rohdaten der Farbpalletten-Einträge. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Liefert die Rohanzahl der Farbpalletten-Einträge. |
| [getTransparentColor()](#getTransparentColor--) | Liefert die transparente Farbe. |
| [getTransparentIndex()](#getTransparentIndex--) | Liefert den Index der transparenten Farbe. |
| [hasTransparentColor()](#hasTransparentColor--) | Ermittelt einen Wert, der angibt, ob eine transparente Farbe vorhanden ist. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Liefert die Rohdaten der Farbpalletten-Einträge.

Wert: Die Rohdaten der Farbpaletteneinträge.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Liefert die Rohanzahl der Farbpalletten-Einträge.

Wert: Die Anzahl der Roh‑Farbpaletteneinträge.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Liefert die transparente Farbe.

Wert: Die transparente Farbe.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Liefert den Index der transparenten Farbe.

Wert: Der Index der transparenten Farbe.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Ermittelt einen Wert, der angibt, ob eine transparente Farbe vorhanden ist.

Wert:  true  wenn transparente Farbe existiert; andernfalls  false .

**Returns:**
boolean
