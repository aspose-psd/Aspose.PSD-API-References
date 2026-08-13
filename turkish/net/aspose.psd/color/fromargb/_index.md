---
title: "Color.FromArgb"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Color yöntemi. 32 bit ARGB değerinden bir Color yapısı oluşturur."
type: docs
weight: 1430
url: /tr/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

32 bit ARGB değerinden bir [`Color`](../) yapısı oluşturur.

```csharp
public static Color FromArgb(int argb)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb | Int32 | 32 bit ARGB değerini belirten bir değer. |

### Dönüş Değeri

Bu yöntemin oluşturduğu [`Color`](../) yapısı.

### Ayrıca Bakınız

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Dört ARGB bileşeni (alfa, kırmızı, yeşil ve mavi) değerlerinden bir [`Color`](../) yapısı oluşturur. Bu yöntem her bileşen için 32 bit bir değer geçirmeye izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha | Int32 | Alfa bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| kırmızı | Int32 | Kırmızı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| yeşil | Int32 | Yeşil bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| mavi | Int32 | Mavi bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

### Dönüş Değeri

Bu yöntemin oluşturduğu [`Color`](../).

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green* veya *blue* 0'dan küçük veya 255'ten büyük. |

### Ayrıca Bakınız

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Belirtilen [`Color`](../) yapısından, yeni belirtilen alfa değeriyle bir [`Color`](../) yapısı oluşturur. Bu yöntem alfa değeri için 32 bit bir değer geçirmeye izin verse de, değer 8 bit ile sınırlıdır.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha | Int32 | Yeni [`Color`](../) için alfa değeri. Geçerli değerler 0 ile 255 arasındadır. |
| baseColor | Color | Yeni [`Color`](../) oluşturulacak [`Color`](../). |

### Dönüş Değeri

Bu yöntemin oluşturduğu [`Color`](../).

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 0'dan küçük veya 255'ten büyük. |

### Ayrıca Bakınız

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Belirtilen 8 bit renk değerlerinden (kırmızı, yeşil ve mavi) bir [`Color`](../) yapısı oluşturur. Alfa değeri dolaylı olarak 255'tir (tamamen opak). Bu yöntem her renk bileşeni için 32 bit bir değer geçirmeye izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| red | Int32 | Yeni [`Color`](../) için kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| green | Int32 | Yeni [`Color`](../) için yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| blue | Int32 | Yeni [`Color`](../) için mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

### Dönüş Değeri

Bu yöntemin oluşturduğu [`Color`](../).

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green* veya *blue* 0'dan küçük ya da 255'ten büyük. |

### Ayrıca Bakınız

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


