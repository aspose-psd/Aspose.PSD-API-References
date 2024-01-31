---
title: CmykColorHelper.ToCmykIcc
second_title: Aspose.PSD for .NET API Reference
description: CmykColorHelper method. The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles
type: docs
weight: 110
url: /net/aspose.psd/cmykcolorhelper/tocmykicc/
---
{{< psd/tize >}}
## ToCmykIcc(Color[], Stream, Stream) {#tocmykicc_3}

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

```csharp
public static int[] ToCmykIcc(Color[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Color[] | The ARGB colors. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color[]) {#tocmykicc_2}

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

```csharp
public static int[] ToCmykIcc(Color[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Color[] | The ARGB colors. |

### Return Value

The CMYK colors presented as 32-bit integer values.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color) {#tocmykicc}

The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

```csharp
public static int ToCmykIcc(Color pixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixel | Color | The ARGB color. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## ToCmykIcc(Color, Stream, Stream) {#tocmykicc_1}

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

```csharp
public static int ToCmykIcc(Color pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixel | Color | The ARGB color. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK color presented as a 32-bit integer value.

### See Also

* struct [Color](../../color/)
* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


