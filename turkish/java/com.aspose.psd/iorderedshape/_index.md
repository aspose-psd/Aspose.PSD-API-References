---
title: "IOrderedShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sıralı bir şekli temsil eder."
type: docs
weight: 129
url: /tr/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Sıralı bir şekli temsil eder. Sıralı bir şekil, bir başlangıç ve bitiş noktasına sahip sürekli bir nokta kümesidir. Belirli bir kural kullanılarak bağlanan sürekli nokta kümesi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Şeklin bitiş noktasını alır. |
| [getStartPoint()](#getStartPoint--) | Şeklin başlangıç noktasını alır. |
| [isClosed()](#isClosed--) | Sıralı şeklin kapalı olup olmadığını gösteren bir değeri alır. |
| [reverse()](#reverse--) | Bu şeklin nokta sırasını tersine çevirir. |
| [setClosed(boolean value)](#setClosed-boolean-) | Sıralı şeklin kapalı olup olmadığını gösteren bir değeri ayarlar. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Şeklin bitiş noktasını alır.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Şeklin başlangıç noktasını alır.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Sıralı şeklin kapalı olup olmadığını gösteren bir değeri alır. Kapalı sıralı şekil işlenirken başlangıç ve bitiş noktaları anlam taşımaz.

**Returns:**
boolean -  true  bu sıralı şekil kapalıysa; aksi takdirde,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Bu şeklin nokta sırasını tersine çevirir.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Sıralı şeklin kapalı olup olmadığını gösteren bir değeri ayarlar. Kapalı sıralı şekil işlenirken başlangıç ve bitiş noktaları anlam taşımaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  bu sıralı şekil kapalıysa; aksi takdirde,  false . |

