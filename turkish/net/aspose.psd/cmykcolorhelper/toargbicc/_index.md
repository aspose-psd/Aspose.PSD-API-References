---
title: "CmykColorHelper.ToArgbIcc"
second_title: "Aspose.PSD for .NET API Referansı"
description: "CmykColorHelper yöntemi. CMYK renklerden ARGB renklere, varsayılan profillerle Icc dönüşümü kullanarak dönüşüm"
type: docs
weight: 80
url: /tr/net/aspose.psd/cmykcolorhelper/toargbicc/
---
{{< psd/tize >}}
## ToArgbIcc(int[]) {#toargbicc_2}

CMYK renklerinden ARGB renklerine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK pikseller 32-bit tam sayı değerleri olarak sunulur. |

### Dönüş Değeri

ARGB renkleri.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

CMYK renklerinden ARGB renklerine, özel profillerle Icc dönüşümü kullanılarak dönüşüm.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixels | Int32[] | CMYK renkleri 32-bit tam sayı değerleri olarak sunulur. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |

### Dönüş Değeri

ARGB renkleri.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int) {#toargbicc}

CMYK renginden ARGB Rengine, varsayılan profillerle Icc dönüşümü kullanılarak dönüşüm.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | Int32 | 32 bit tamsayı değeri olarak sunulan CMYK rengi. |

### Dönüş Değeri

ARGB rengi.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

CMYK renginden ARGB rengine, özel profil ile Icc dönüşümü kullanılarak dönüşüm.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmykPixel | Int32 | 32 bit tamsayı değeri olarak sunulan CMYK rengi. |
| cmykIccStream | Stream | CMYK Icc profilini içeren akış. |
| rgbIccStream | Stream | RGB Icc profilini içeren akış. |

### Dönüş Değeri

ARGB rengi.

### Ayrıca Bakınız

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


