---
title: "CmykColorHelper.ToCmykIcc"
second_title: "Aspose.PSD for .NET API Referansı"
description: "CmykColorHelper yöntemi. Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm"
type: docs
weight: 110
url: /tr/net/aspose.psd/cmykcolorhelper/tocmykicc/
---
{{< psd/tize >}}
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

Özel profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | Color[] | ARGB renkleri. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |

### Dönüş Değeri

CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renklerinden CMYK renklerine dönüşüm.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pikseller | Color[] | ARGB renkleri. |

### Dönüş Değeri

CMYK renkleri 32-bit tam sayı değerleri olarak sunulur.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

Varsayılan profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | Renk | ARGB rengi. |

### Dönüş Değeri

32 bit tamsayı değeri olarak sunulan CMYK rengi.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

Özel profillerle Icc dönüşümü kullanarak ARGB renginden CMYK rengine dönüşüm.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| piksel | Renk | ARGB rengi. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |

### Dönüş Değeri

32 bit tamsayı değeri olarak sunulan CMYK rengi.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


