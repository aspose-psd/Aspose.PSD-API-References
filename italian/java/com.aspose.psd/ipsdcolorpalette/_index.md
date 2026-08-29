---
title: "IPsdColorPalette"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La tavolozza dei colori pasd"
type: docs
weight: 134
url: /it/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

La tavolozza dei colori pasd
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Restituisce i dati grezzi delle voci della tavolozza dei colori. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Restituisce il conteggio grezzo delle voci della tavolozza dei colori. |
| [getTransparentColor()](#getTransparentColor--) | Restituisce il colore trasparente. |
| [getTransparentIndex()](#getTransparentIndex--) | Restituisce l'indice del colore trasparente. |
| [hasTransparentColor()](#hasTransparentColor--) | Restituisce un valore che indica se esiste un colore trasparente. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Restituisce i dati grezzi delle voci della tavolozza dei colori.

Valore: I dati grezzi delle voci della tavolozza dei colori.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Restituisce il conteggio grezzo delle voci della tavolozza dei colori.

Valore: Il conteggio grezzo delle voci della tavolozza dei colori.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Restituisce il colore trasparente.

Valore: Il colore trasparente.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Restituisce l'indice del colore trasparente.

Valore: L'indice del colore trasparente.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Restituisce un valore che indica se esiste un colore trasparente.

Valore:  true  se il colore trasparente esiste; altrimenti,  false .

**Returns:**
boolean
