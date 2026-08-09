---
title: "IPsdColorPalette"
second_title: "Java için Aspose.PSD API Referansı"
description: "Pasd renk paleti"
type: docs
weight: 134
url: /tr/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

Pasd renk paleti
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Ham renk paleti giriş verilerini alır. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Ham renk paleti giriş sayısını alır. |
| [getTransparentColor()](#getTransparentColor--) | Şeffaf rengi alır. |
| [getTransparentIndex()](#getTransparentIndex--) | Şeffaf rengin dizinini alır. |
| [hasTransparentColor()](#hasTransparentColor--) | Şeffaf rengin mevcut olup olmadığını gösteren bir değer alır. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Ham renk paleti giriş verilerini alır.

Değer: Ham renk paleti giriş verileri.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Ham renk paleti giriş sayısını alır.

Değer: Ham renk paleti giriş sayısı.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Şeffaf rengi alır.

Değer: Şeffaf renk.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Şeffaf rengin dizinini alır.

Değer: Şeffaf rengin indeksi.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Şeffaf rengin mevcut olup olmadığını gösteren bir değer alır.

Değer:  true  eğer saydam renk mevcutsa; aksi takdirde,  false .

**Returns:**
boolean
