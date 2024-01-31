---
title: CmykColorHelper.ToArgbIcc
second_title: Aspose.PSD for .NET API Reference
description: CmykColorHelper method. The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles
type: docs
weight: 80
url: /net/aspose.psd/cmykcolorhelper/toargbicc/
---
{{< psd/tize >}}
## ToArgbIcc(int[]) {#toargbicc_2}

The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | The CMYK pixels presented as 32-bit integer values. |

### Return Value

The ARGB colors.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int[], Stream, Stream) {#toargbicc_3}

The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

```csharp
public static Color[] ToArgbIcc(int[] cmykPixels, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | Int32[] | The CMYK colors presented as 32-bit integer values. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |

### Return Value

The ARGB colors.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int) {#toargbicc}

The conversion from CMYK color to ARGB Color using Icc conversion with default profiles.

```csharp
public static Color ToArgbIcc(int cmykPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | The CMYK color presented as a 32-bit integer value. |

### Return Value

The ARGB color.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToArgbIcc(int, Stream, Stream) {#toargbicc_1}

The conversion from CMYK color to ARGB color using Icc conversion with custom profile.

```csharp
public static Color ToArgbIcc(int cmykPixel, Stream cmykIccStream, Stream rgbIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | Int32 | The CMYK color presented as a 32-bit integer value. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |

### Return Value

The ARGB color.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


