---
title: Color.FromArgb
second_title: Aspose.PSD for .NET API Referansı
description: Color yöntem. oluştururColor 32 bit ARGB değerinden yapı.
type: docs
weight: 1430
url: /tr/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

oluşturur[`Color`](../) 32 bit ARGB değerinden yapı.

```csharp
public static Color FromArgb(int argb)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| argb | Int32 | 32 bit ARGB değerini belirten bir değer. |

### Geri dönüş değeri

bu[`Color`](../) Bu yöntemin oluşturduğu yapı.

### Ayrıca bakınız

* struct [Color](../)
* ad alanı [Aspose.PSD](../../color/)
* toplantı [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

oluşturur[`Color`](../) dört ARGB bileşeni (alfa, kırmızı, yeşil ve mavi) değerlerinden yapı. Bu yöntem her bileşen için 32 bitlik bir değerin iletilmesine izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| alpha | Int32 | alfa bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| red | Int32 | Kırmızı bileşen. Geçerli değerler 0 ile 255 arasındadır. |
| green | Int32 | Yeşil bileşen. Geçerli değerler 0 ile 255 arasındadır. |
| blue | Int32 | mavi bileşen. Geçerli değerler 0 ile 255 arasındadır. |

### Geri dönüş değeri

bu[`Color`](../) bu yöntemin oluşturduğu.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , veya*blue* 0'dan küçük veya 255'ten büyük. |

### Ayrıca bakınız

* struct [Color](../)
* ad alanı [Aspose.PSD](../../color/)
* toplantı [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

oluşturur[`Color`](../) belirtilen yapı[`Color`](../) yapı, ancak belirtilen yeni alfa değeriyle. Bu yöntem, alfa değeri için 32 bitlik bir değerin geçmesine izin verse de, değer 8 bit ile sınırlıdır.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| alpha | Int32 | Yeni için alfa değeri[`Color`](../). Geçerli değerler 0 ile 255 arasındadır. |
| baseColor | Color | bu[`Color`](../) yenisini yaratmak için[`Color`](../). |

### Geri dönüş değeri

bu[`Color`](../) bu yöntemin oluşturduğu.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 0'dan küçük veya 255'ten büyük. |

### Ayrıca bakınız

* struct [Color](../)
* ad alanı [Aspose.PSD](../../color/)
* toplantı [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

oluşturur[`Color`](../) belirtilen 8 bitlik renk değerlerinden (kırmızı, yeşil ve mavi) yapı. Alfa değeri dolaylı olarak 255'tir (tamamen opak). Bu yöntem, her renk bileşeni için 32 bitlik bir değerin iletilmesine izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| red | Int32 | Yeni için kırmızı bileşen değeri[`Color`](../). Geçerli değerler 0 ile 255 arasındadır. |
| green | Int32 | Yeni için yeşil bileşen değeri[`Color`](../). Geçerli değerler 0 ile 255 arasındadır. |
| blue | Int32 | Yeni için mavi bileşen değeri[`Color`](../). Geçerli değerler 0 ile 255 arasındadır. |

### Geri dönüş değeri

bu[`Color`](../) bu yöntemin oluşturduğu.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , veya*blue* 0'dan küçük veya 255'ten büyük. |

### Ayrıca bakınız

* struct [Color](../)
* ad alanı [Aspose.PSD](../../color/)
* toplantı [Aspose.PSD](../../../)


